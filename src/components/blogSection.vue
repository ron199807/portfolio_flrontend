
Copy
<template>
  <div class="blog-post">
    <!-- Blog Content -->
    <h1>{{ title }}</h1>
    <p>{{ content }}</p>

    <!-- Comment Section -->
    <div class="comments">
      <h2>Comments</h2>
      <ul v-if="comments.length">
        <li v-for="(comment, index) in comments" :key="index">
          <strong>{{ comment.name }}</strong>: {{ comment.message }}
          <small>({{ formatDate(comment.created_at) }})</small>
        </li>
      </ul>
      <p v-else>No comments yet. Be the first to comment!</p>

      <!-- Comment Form -->
      <form @submit.prevent="addComment">
        <input v-model="newComment.name" type="text" placeholder="Your Name" required />
        <textarea v-model="newComment.message" placeholder="Your Comment" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </div>
  </div>
</template>

<script>
import axios from "axios";

export default {
  data() {
    return {
      title: "",
      content: "",
      comments: [],
      newComment: {
        name: "",
        message: "",
      },
    };
  },
  async created() {
    // Fetch blog post and comments when the component is created
    await this.fetchBlogPost();
    await this.fetchComments();
  },
  methods: {
    async fetchBlogPost() {
      try {
        const response = await axios.get("http://localhost:8000/api/blog/");
        this.title = response.data.title;
        this.content = response.data.content;
      } catch (error) {
        console.error("Error fetching blog post:", error);
      }
    },
    async fetchComments() {
      try {
        const response = await axios.get("http://localhost:8000/api/comments/");
        this.comments = response.data;
      } catch (error) {
        console.error("Error fetching comments:", error);
      }
    },
    async addComment() {
      if (this.newComment.name && this.newComment.message) {
        try {
          const response = await axios.post("http://localhost:8000/api/comments/", this.newComment);
          this.comments.push(response.data); // Add the new comment to the list
          this.newComment.name = ""; // Clear the form
          this.newComment.message = "";
        } catch (error) {
          console.error("Error adding comment:", error);
        }
      }
    },
    formatDate(dateString) {
      const date = new Date(dateString);
      return date.toLocaleString(); // Format the date as needed
    },
  },
};
</script>

<style scoped>
.blog-post {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  font-family: Arial, sans-serif;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

p {
  font-size: 1.2rem;
  line-height: 1.6;
}

.comments {
  margin-top: 40px;
}

h2 {
  font-size: 1.8rem;
  margin-bottom: 20px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  background: #f9f9f9;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
}

form {
  display: flex;
  flex-direction: column;
}

input,
textarea {
  margin-bottom: 10px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 10px;
  background: #42b983;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background: #369f6e;
}
</style>