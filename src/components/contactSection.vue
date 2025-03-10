<template>
    <section class="contact" id="contact">
      <div class="container">
        <div class="contact-grid">
          <div class="contact-info">
            <h2 class="contact-title">Got a project? Let's talk.</h2>
            <p class="contact-description">
              I'm a passionate web developer with more than 8 years of experience in application development, interface design, and user experience.
            </p>
            <a href="mailto:contact@example.com" class="link-yellow">
              hezalabs.com
              <arrow-right-icon class="icon" />
            </a>
          </div>
          <div class="contact-form">
            <h2 class="contact-title">Estimate your project? Let me know here.</h2>
            <form>
              <div class="form-group">
                <label for="name">What's your name?</label>
                <input type="text" id="name" name="name" />
              </div>
              <div class="form-group">
                <label for="email">Your fancy email</label>
                <input type="email" id="email" name="email" />
              </div>
              <div class="form-group">
                <label for="message">Tell me about your project</label>
                <textarea id="message" name="message"></textarea>
                <button type="submit" class="btn-submit">
                  <arrow-right-icon class="icon" />
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script setup>
  import { ArrowRight as ArrowRightIcon } from 'lucide-vue-next';
  </script>
  
  <style scoped>
  /* Add scoped styles for the contact component */
  </style>