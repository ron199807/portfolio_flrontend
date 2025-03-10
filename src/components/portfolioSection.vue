<template>
    <section class="portfolio" id="works">
      <div class="container">
        <div class="section-label">— PORTFOLIO</div>
        <h2 class="section-title">All Creative Works, Selected projects.</h2>
        <p class="section-description">
          I'm a passionate web developer with more than 5 years of experience in application development, interface design, and user experience.
        </p>
        <a href="#more-works" class="btn-primary">
          Explore more
          <arrow-right-icon class="icon" />
        </a>
  
        <div class="portfolio-grid">
          <div class="portfolio-item large">
            <div class="portfolio-content">
              <h3 class="portfolio-title">fitness app</h3>
              <p class="portfolio-category">Created with React</p>
              
            </div>
            <img src="../assets/fitness.jpg" alt="fitness image" class="portfolio-image-placeholder" />
            <a href="https://nameless-trackingsystem.web.val.run">view</a>
          </div>
            
          <div class="portfolio-item">
            <div class="portfolio-content">
              <h3 class="portfolio-title"></h3>
              <p class="portfolio-category">Global cuisines</p>
            </div>
            <div class="portfolio-image-placeholder"></div>
            <a href="https://nameless-globalcuisinesite.web.val.run">view</a>
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
 
  </style>