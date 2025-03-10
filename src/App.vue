<template>
  <div class="portfolio-website">
    <TheHeader />
    <TheHero />
    <ExpertiseSection />
    <CreativeSection />
    <ServiceSection />
    <PortfolioSection />
    <BlogSection />
    <TestimonialSection />
    <ContactSection />
    <FooterSection />
  </div>
</template>

<script>


import TestimonialSection from './components/testimonialSection.vue';
import FooterSection from './components/footerSection.vue';
import ContactSection from './components/contactSection.vue';
import BlogSection from './components/blogSection.vue';
import PortfolioSection from './components/portfolioSection.vue';
import ServiceSection from './components/serviceSection.vue';
import CreativeSection from './components/creativeSection.vue';
import ExpertiseSection from './components/expertiseSection.vue';
import TheHero from './components/TheHero.vue';
import TheHeader from './components/TheHeader.vue';
export default {
  name: 'App',
  components: {
    TheHeader,
    TheHero,
    ExpertiseSection,
    CreativeSection,
    ServiceSection,
    PortfolioSection,
    BlogSection,
    TestimonialSection,
    ContactSection,
    FooterSection,
  }
}
</script>


