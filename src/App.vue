<script setup>
import Navbar from './components/Navbar.vue'
import About from './components/About.vue'
import Carousel from './components/Carousel.vue'
import Product from './components/Product.vue'
import Contact from './components/Contact.vue'

</script>

<template>
 
  <Navbar/>
  <About/>
  <Carousel/>
  <Product/>
  <Contact/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
