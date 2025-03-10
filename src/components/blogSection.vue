<template>
    <section class="blog" id="blog">
      <div class="container">
        <div class="section-label">— BLOG</div>
        <h2 class="section-title">What's new? My blog and news.</h2>
  
        <div class="blog-list">
          <div class="blog-item">
            <div class="blog-date">Feb 25, 2023</div>
            <div class="blog-category">Blog</div>
            <h3 class="blog-title">Let Me be a lesson to you</h3>
            <arrow-right-icon class="icon" />
          </div>
          <div class="blog-item">
            <div class="blog-date">Feb 22, 2023</div>
            <div class="blog-category">Blog</div>
            <h3 class="blog-title">How do you use time tracking for projects?</h3>
            <arrow-right-icon class="icon" />
          </div>
          <div class="blog-item">
            <div class="blog-date">Feb 4, 2023</div>
            <div class="blog-category">Blog</div>
            <h3 class="blog-title">Ego and empathy in design</h3>
            <arrow-right-icon class="icon" />
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script setup>
  import { ArrowRight as ArrowRightIcon } from 'lucide-vue-next';
  </script>
  
  <style scoped>
  /* Add scoped styles for the blog component */
  </style>