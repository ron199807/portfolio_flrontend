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
            <img src="../assets/workout-plan.jpg" alt="fitness image" class="portfolio-image-placeholder" />
            <div class="link-container">
              <a href="https://nameless-trackingsystem.web.val.run" class="project-link">view</a>
              <arrow-right-icon class="icon" />
            </div>
          </div>
            
          <div class="portfolio-item">
            <div class="portfolio-content">
              <h3 class="portfolio-title"></h3>
              <p class="portfolio-category">Global cuisines</p>
            </div>
            <img src="../assets/global-cuisines.png" class="portfolio-image-placeholder" />
            <div class="link-container">
              <a href="https://nameless-globalcuisinesite.web.val.run" class="project-link">view</a>
              <arrow-right-icon class="icon" />
            </div>
          </div>
          <div class="portfolio-item">
            <div class="portfolio-content">
              <h3 class="portfolio-title">Simple-Weather-App</h3>
              <p class="portfolio-category">Product Developer</p>
            </div>
            <img src="../assets/Simple-Weather-App.png" class="portfolio-image-placeholder"></div>
            <div class="link-container">
              <a href="https://https://nameless-weatherapp.web.val.run" class="project-link">view</a>
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
 
  </style>