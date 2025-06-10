<template>
  <div class="font-sans antialiased">
    <Navbar />
    <HeroSection />
    <About />
    <Projects />
    <Clients />
    <Blog />
    <ContactForm />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import HeroSection from './components/HeroSection.vue';
import About from './components/About.vue';
import Projects from './components/Projects.vue';
import Clients from './components/Clients.vue';
import Blog from './components/Blog.vue';
import ContactForm from './components/ContactForm.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    HeroSection,
    About,
    Projects,
    Clients,
    Blog,
    ContactForm,
    Footer
  }
}
</script>
