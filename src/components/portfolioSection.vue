<template>
    <section class="portfolio" id="works">
      <div class="container">
        <div class="section-label">— PORTFOLIO</div>
        <h2 class="section-title">All Creative Works, Selected projects.</h2>
        <p class="section-description">
          I'm a passionate web developer with more than 8 years of experience in application development, interface design, and user experience.
        </p>
        <a href="#more-works" class="btn-primary">
          Explore more
          <arrow-right-icon class="icon" />
        </a>
  
        <div class="portfolio-grid">
          <div class="portfolio-item large">
            <div class="portfolio-content">
              <h3 class="portfolio-title">Seone.</h3>
              <p class="portfolio-category">Portfolio Development</p>
            </div>
            <div class="portfolio-image-placeholder"></div>
          </div>
          <div class="portfolio-item">
            <div class="portfolio-content">
              <h3 class="portfolio-title">BeServer.</h3>
              <p class="portfolio-category">Branding Project</p>
            </div>
            <div class="portfolio-image-placeholder"></div>
          </div>
          <div class="portfolio-item">
            <div class="portfolio-content">
              <h3 class="portfolio-title">Energetic Tumbler.</h3>
              <p class="portfolio-category">Product Development</p>
            </div>
            <div class="portfolio-image-placeholder"></div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script setup>
  import { ArrowRight as ArrowRightIcon } from 'lucide-vue-next';
  </script>
  
  <style scoped>
  /* Add scoped styles for the portfolio component */
  </style>