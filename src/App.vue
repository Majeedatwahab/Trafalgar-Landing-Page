<script setup>
import { RouterLink, RouterView } from 'vue-router';
import OurServices from './components/OurServices.vue';
import LeadingHealthcare from './components/LeadingHealthcare.vue';
import DownloadApp from './components/DownloadApp.vue';
import ReviewCards from './components/ReviewCards.vue';
import ArticleSection from './components/ArticleSection.vue';
import FooterSection from './components/FooterSection.vue';
import HeroSection from './components/HeroSection.vue';

</script>

<template>
  <header class="header">
    <div class="container">
      <div class="logo">
    <img src="./assets/images/logo.png" alt="trafalgar-logo" />
  </div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/">Find a Hospital</RouterLink>
        <RouterLink to="/">Apps</RouterLink>
        <RouterLink to="/">Testimonials</RouterLink>
        <RouterLink to="/">About Us</RouterLink>
      </nav>
    </div>
  
 
  </header>

  <RouterView />
  <HeroSection />
  <OurServices />
  <LeadingHealthcare />
  <DownloadApp />
  <ReviewCards />
  <ArticleSection />
  <FooterSection />
</template>

<style scoped>
.header {
  background-color: #fff;
  padding: 10px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.logo img {
  max-width: 100px;
  height: auto;
}

nav {
  display: flex;
  gap: 20px;
}

nav a {
  text-decoration: none;
  color: #7D7987;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #1F1534;
}

/* Responsive Styling */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
    align-items: flex-start;
    padding: 10px;
  }

  .logo {
    margin-bottom: 10px;
  }

  nav {
    flex-direction: column;
    gap: 10px;
  }

  nav a {
    font-size: 14px;
  }
}
</style>
