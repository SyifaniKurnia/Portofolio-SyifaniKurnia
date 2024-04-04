<template>
  <div>
    <Navbar />
    <Home />
    <About />
    <Background />
    <Project />
    <Experience />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import Home from "./views/HomeView.vue";
import About from "./views/AboutView.vue";
import Background from "./views/BackgroundView.vue";
import Project from "./views/ProjectView.vue";
import Experience from "./views/ExperienceView.vue";
import Footer from "./components/Footer.vue";
</script>
