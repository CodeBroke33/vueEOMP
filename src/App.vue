<template>
  <main class="container-fluid">
    <router-view/>
  </main>
  <!-- <nav>
    <router-link to="/">Home</router-link>  |
    <router-link to="/about">About</router-link>  |
    <router-link to="/resume">Resume</router-link>  |
    <router-link to="/project">Projects</router-link>  |
    <router-link to="/testimonial">Testimonials</router-link>  |
    <router-link to="/reachme">Reach Me</router-link>  |
  </nav> -->
  <FooterView />
  <NavBar />
</template>

<script>
import NavBar from './components/NavBar.vue'; 
import FooterView from './components/FooterView.vue';

export default {
  components: {
   FooterView, 
   NavBar,
}
}
</script>

<style src="@/assets/CSS/style.css">

</style>
