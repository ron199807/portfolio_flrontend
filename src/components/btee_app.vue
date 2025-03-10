<template>
    <div class="portfolio-website">
      <!-- Header/Navigation -->
      <header class="header">
        <div class="container">
          <div class="logo">
            <img src="../assets/ron22.png" alt="Logo" class="logo-placeholder" />
            <!-- Using a placeholder logo since we can't extract the actual logo -->
          </div>
          <nav class="navigation">
            <ul>
              <li class="active"><a href="#services">Services</a></li>
              <li><a href="#works">Works</a></li>
              <li><a href="#blog">Blog</a></li>
            </ul>
          </nav>
        </div>
      </header>
  
      <!-- Hero Section -->
      <section class="hero">
        <div class="container">
          <div class="hero-content">
            <div class="hero-text">
              <div class="section-label">— INTRODUCTION</div>
              <h1 class="hero-title">
                Product Designer and Developer, based in Lusaka
              </h1>
              <p class="hero-description">
                I'm a passionate web developer with more than 5 years of experience in application development, interface design, and user experience.
              </p>
              <a href="#contact" class="btn-primary">
                My story
                <arrow-right-icon class="icon" />
              </a>
            </div>
            <div class="hero-image">
              <img src="../assets/ronald.jpg" alt="Ronald Mweema" class="image-placeholder" />
              <!-- Using a placeholder since we can't extract the actual image -->
            </div>
          </div>
        </div>
      </section>
  
      <!-- Expertise Section -->
      <section class="expertise" id="services">
        <div class="container">
          <div class="section-label">— EXPERTISE</div>
          <h2 class="section-title">Any Type Of Query & Discussion.</h2>
          <p class="section-description">
            I'm a passionate web developer with more than 5 years of experience in application development, interface design, and user experience.
          </p>
          <a href="#contact" class="link-yellow">
            hezalabs.com
            <arrow-right-icon class="icon" />
          </a>
        </div>
      </section>
  
      <!-- Creative Section -->
      <section class="creative">
        <div class="container">
          <div class="creative-content">
            <h2 class="creative-title">
              You can be creative, but more, you can have in your significant mind.
            </h2>
            <p class="creative-description">
              I'm a passionate web developer with more than 5 years of experience in application development, interface design, and user experience.
            </p>
          </div>
          <div class="stats">
            <div class="stat-item">
              <div class="stat-number">14</div>
              <div class="stat-label">Years of Experience</div>
            </div>
            <div class="stat-item">
              <div class="stat-number">187</div>
              <div class="stat-label">Completed Projects</div>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Services Cards -->
      <section class="services">
        <div class="container">
          <div class="services-grid">
            <div class="service-card yellow">
              <circle-icon class="service-icon" />
              <h3 class="service-title">Product Designer</h3>
              <p class="service-count">124 Projects</p>
            </div>
            <div class="service-card">
              <tag-icon class="service-icon" />
              <h3 class="service-title">Branding Designer</h3>
              <p class="service-count">37 Projects</p>
            </div>
            <div class="service-card">
              <monitor-icon class="service-icon" />
              <h3 class="service-title">Full Stack Developer</h3>
              <p class="service-count">42 Projects</p>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Clients Section
      <section class="clients">
        <div class="container">
          <div class="clients-grid">
            <img src="https://hebbkx1anhila5yf.public.blob.vercel-storage.com/11ff180e-1970-47e7-be11-54599826bdb3.jpg-COAvxIYxNWDktbnlmpdrbjIkYy9ge4.jpeg" alt="IBM" class="hidden" />
            <div class="client-logo">IBM</div>
            <div class="client-logo">IBM Watson</div>
            <div class="client-logo">The Economist</div>
            <div class="client-logo">LONGREAD</div>
            <div class="client-logo">BBC AMERICA</div>
            <div class="client-logo">Medium</div>
            <div class="client-logo">National Geographic</div>
            <div class="client-logo">tumblr.</div>
          </div>
        </div>
      </section> -->
  
      <!-- Portfolio Section -->
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
  
      <!-- Blog Section -->
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
  
      <!-- Testimonial Section -->
      <section class="testimonial">
        <div class="container">
          <div class="testimonial-grid">
            <div class="testimonial-image">
              <div class="image-placeholder"></div>
            </div>
            <div class="testimonial-content">
              <div class="testimonial-text">
                <p>
                  Amazing! At vero eos et accu samus et iusto odio dignissimson ducimus qui
                  blan ditiis praesen tium volup capoten nise no kamani xuc xuc hohoho!
                </p>
              </div>
              <div class="testimonial-author">
                <h4>Jesse Warner</h4>
                <p>CEO at Panoply</p>
              </div>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Contact Section -->
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
  
      <!-- Footer -->
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
    </div>
  </template>
  
  <script setup>
  // import { ref } from 'vue';
  import { 
    ArrowRight as ArrowRightIcon,
    Circle as CircleIcon,
    Tag as TagIcon,
    Monitor as MonitorIcon,
    Twitter as TwitterIcon,
    Instagram as InstagramIcon,
    Linkedin as LinkedinIcon
  } from 'lucide-vue-next';
  </script>
  
  <style>
  :root {
    --color-dark: #1e2330;
    --color-darker: #171c27;
    --color-yellow: #ffc045;
    --color-yellow-dark: #e6a93b;
    --color-text: #ffffff;
    --color-text-muted: #a0a7b7;
    --font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    --spacing-section: 5rem;
  }
  
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: var(--font-primary);
    background-color: var(--color-dark);
    color: var(--color-text);
    line-height: 1.6;
  }
  
  .portfolio-website {
    background-color: var(--color-dark);
    overflow-x: hidden;
  }
  
  .container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1.5rem;
  }
  
  .hidden {
    height: 5rem;
  }
  
  /* Header */
  .header {
    padding: 1.5rem 0;
    position: sticky;
    top: 0;
    z-index: 100;
    background-color: var(--color-dark);
  }
  
  .header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .logo-placeholder {
    width: 2.5rem;
    height: 2.5rem;
    border-radius: .3rem;
  }
  
  .navigation ul {
    display: flex;
    list-style: none;
    gap: 2rem;
  }
  
  .navigation a {
    color: var(--color-text);
    text-decoration: none;
    font-size: 0.9rem;
    transition: color 0.3s;
  }
  
  .navigation a:hover,
  .navigation li.active a {
    color: var(--color-yellow);
  }
  
  /* Hero Section */
  .hero {
    padding: 5rem 0;
  }
  
  .hero-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    align-items: center;
  }
  
  .section-label {
    color: var(--color-text-muted);
    font-size: 0.8rem;
    margin-bottom: 1rem;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  
  .hero-title {
    font-size: 2.5rem;
    line-height: 1.2;
    margin-bottom: 1.5rem;
    font-weight: 700;
  }
  
  .hero-description {
    color: var(--color-text-muted);
    margin-bottom: 2rem;
    max-width: 90%;
  }
  
  .btn-primary {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    color: var(--color-yellow);
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
  }
  
  .btn-primary:hover {
    color: var(--color-yellow-dark);
  }
  
  .icon {
    width: 1rem;
    height: 1rem;
  }
  
  .image-placeholder {
    width: 100%;
    height: 400px;
    background-color: var(--color-darker);
    border-radius: 8px;
    position: relative;
    overflow: hidden;
  }
  
  .image-placeholder::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(45deg, rgba(255, 192, 69, 0.2), transparent);
  }
  
  /* Expertise Section */
  .expertise {
    padding: var(--spacing-section) 0;
    background-color: var(--color-darker);
  }
  
  .section-title {
    font-size: 2rem;
    line-height: 1.3;
    margin-bottom: 1.5rem;
    max-width: 80%;
  }
  
  .section-description {
    color: var(--color-text-muted);
    margin-bottom: 1.5rem;
    max-width: 70%;
  }
  
  .link-yellow {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    color: var(--color-yellow);
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
  }
  
  .link-yellow:hover {
    color: var(--color-yellow-dark);
  }
  
  /* Creative Section */
  .creative {
    padding: var(--spacing-section) 0;
  }
  
  .creative-content {
    margin-bottom: 3rem;
  }
  
  .creative-title {
    font-size: 2rem;
    line-height: 1.3;
    margin-bottom: 1.5rem;
    max-width: 80%;
  }
  
  .creative-description {
    color: var(--color-text-muted);
    max-width: 70%;
  }
  
  .stats {
    display: flex;
    gap: 5rem;
  }
  
  .stat-number {
    font-size: 3rem;
    font-weight: 700;
    color: var(--color-yellow);
    margin-bottom: 0.5rem;
  }
  
  .stat-label {
    color: var(--color-text-muted);
    font-size: 0.9rem;
  }
  
  /* Services Cards */
  .services {
    padding: 0 0 var(--spacing-section);
  }
  
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
  }
  
  .service-card {
    background-color: var(--color-darker);
    padding: 2.5rem;
    border-radius: 8px;
    transition: transform 0.3s;
  }
  
  .service-card:hover {
    transform: translateY(-5px);
  }
  
  .service-card.yellow {
    background-color: var(--color-yellow);
    color: var(--color-dark);
  }
  
  .service-icon {
    margin-bottom: 1.5rem;
    width: 1.5rem;
    height: 1.5rem;
  }
  
  .service-title {
    font-size: 1.25rem;
    margin-bottom: 0.5rem;
  }
  
  .service-count {
    font-size: 0.9rem;
    opacity: 0.7;
  }
  
  /* Clients Section */
  .clients {
    padding: var(--spacing-section) 0;
    background-color: var(--color-darker);
  }
  
  .clients-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 2rem;
    align-items: center;
    justify-items: center;
  }
  
  .client-logo {
    color: var(--color-text-muted);
    font-weight: 600;
    font-size: 1rem;
    transition: color 0.3s;
  }
  
  .client-logo:hover {
    color: var(--color-text);
  }
  
  /* Portfolio Section */
  .portfolio {
    padding: var(--spacing-section) 0;
  }
  
  .portfolio-grid {
    margin-top: 3rem;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5rem;
  }
  
  .portfolio-item {
    background-color: var(--color-darker);
    border-radius: 8px;
    overflow: hidden;
    position: relative;
  }
  
  .portfolio-item.large {
    grid-column: span 1;
    grid-row: span 2;
  }
  
  .portfolio-content {
    padding: 1.5rem;
    position: relative;
    z-index: 2;
  }
  
  .portfolio-title {
    font-size: 1.25rem;
    margin-bottom: 0.5rem;
  }
  
  .portfolio-category {
    font-size: 0.8rem;
    color: var(--color-text-muted);
  }
  
  .portfolio-image-placeholder {
    width: 100%;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.2);
  }
  
  .portfolio-item.large .portfolio-image-placeholder {
    height: 400px;
  }
  
  /* Blog Section */
  .blog {
    padding: var(--spacing-section) 0;
    background-color: var(--color-darker);
  }
  
  .blog-list {
    margin-top: 3rem;
  }
  
  .blog-item {
    display: grid;
    grid-template-columns: 100px 80px 1fr 30px;
    align-items: center;
    padding: 1.5rem 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  }
  
  .blog-date {
    font-size: 0.8rem;
    color: var(--color-text-muted);
  }
  
  .blog-category {
    font-size: 0.8rem;
    color: var(--color-text-muted);
  }
  
  .blog-title {
    font-size: 1rem;
    font-weight: 500;
  }
  
  .blog-item .icon {
    color: var(--color-yellow);
    opacity: 0;
    transition: opacity 0.3s;
  }
  
  .blog-item:hover .icon {
    opacity: 1;
  }
  
  /* Testimonial Section */
  .testimonial {
    padding: var(--spacing-section) 0;
  }
  
  .testimonial-grid {
    display: grid;
    grid-template-columns: 300px 1fr;
    gap: 3rem;
    align-items: center;
  }
  
  .testimonial-text {
    font-size: 1.5rem;
    line-height: 1.4;
    margin-bottom: 2rem;
  }
  
  .testimonial-author h4 {
    font-size: 1.1rem;
    margin-bottom: 0.25rem;
  }
  
  .testimonial-author p {
    font-size: 0.9rem;
    color: var(--color-text-muted);
  }
  
  /* Contact Section */
  .contact {
    padding: var(--spacing-section) 0;
    background-color: var(--color-darker);
  }
  
  .contact-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 3rem;
  }
  
  .contact-title {
    font-size: 2rem;
    line-height: 1.3;
    margin-bottom: 1.5rem;
  }
  
  .contact-description {
    color: var(--color-text-muted);
    margin-bottom: 1.5rem;
  }
  
  .form-group {
    margin-bottom: 1.5rem;
    position: relative;
  }
  
  .form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-size: 0.9rem;
  }
  
  .form-group input,
  .form-group textarea {
    width: 100%;
    padding: 0.75rem 0;
    background: transparent;
    border: none;
    border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    color: var(--color-text);
    font-family: var(--font-primary);
    font-size: 1rem;
    transition: border-color 0.3s;
  }
  
  .form-group input:focus,
  .form-group textarea:focus {
    outline: none;
    border-color: var(--color-yellow);
  }
  
  .form-group textarea {
    min-height: 100px;
    resize: none;
  }
  
  .btn-submit {
    position: absolute;
    bottom: 1rem;
    right: 0;
    background: var(--color-yellow);
    color: var(--color-dark);
    border: none;
    width: 2.5rem;
    height: 2.5rem;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  .btn-submit:hover {
    background-color: var(--color-yellow-dark);
  }
  
  /* Footer */
  .footer {
    padding: 3rem 0;
    text-align: center;
  }
  
  .footer .logo {
    display: flex;
    justify-content: center;
    margin-bottom: 1rem;
  }
  
  .footer-text {
    color: var(--color-text-muted);
    font-size: 0.9rem;
    margin-bottom: 1.5rem;
  }
  
  .social-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
  }
  
  .social-link {
    color: var(--color-text-muted);
    transition: color 0.3s;
  }
  
  .social-link:hover {
    color: var(--color-yellow);
  }
  
  /* Responsive */
  @media (max-width: 992px) {
    .hero-content,
    .contact-grid,
    .testimonial-grid {
      grid-template-columns: 1fr;
    }
    
    .section-title,
    .hero-title,
    .creative-title,
    .contact-title {
      max-width: 100%;
    }
    
    .section-description,
    .hero-description {
      max-width: 100%;
    }
    
    .portfolio-grid {
      grid-template-columns: 1fr;
    }
    
    .portfolio-item.large {
      grid-column: span 1;
    }
  }
  
  @media (max-width: 768px) {
    .services-grid {
      grid-template-columns: 1fr;
    }
    
    .blog-item {
      grid-template-columns: 80px 60px 1fr 20px;
    }
    
    .stats {
      flex-direction: column;
      gap: 2rem;
    }
  }
  
  @media (max-width: 576px) {
    .blog-item {
      grid-template-columns: 1fr;
      gap: 0.5rem;
    }
    
    .blog-date, .blog-category {
      margin-bottom: 0.5rem;
    }
    
    .blog-item .icon {
      display: none;
    }
  }
  </style>