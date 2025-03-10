<template>
    <footer class="footer">
      <div class="container">
        <div class="logo">
          <img src="../assets/ron22.png" alt="Ronald Mweema" class="logo-placeholder" />
        </div>
        <p class="footer-text">Powered by nothing. Just a human.</p>
        <div class="social-links">
          <a href="#" class="social-link">
            <twitter-icon class="icon" />
          </a>
          <a href="#" class="social-link">
            <instagram-icon class="icon" />
          </a>
          <a href="#" class="social-link">
            <linkedin-icon class="icon" />
          </a>
        </div>
      </div>
    </footer>
  </template>
  
  <script setup>
  import { Twitter as TwitterIcon, Instagram as InstagramIcon, Linkedin as LinkedinIcon } from 'lucide-vue-next';
  </script>
  
  <style scoped>
  /* Add scoped styles for the footer component */
  </style>