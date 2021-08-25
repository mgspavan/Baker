<template>
 
  <Home />
  <About/>
  <Products/>
  <Contact/>
 
</template>

<script>
import About from './components/About.vue'
import Home from './components/Home.vue'
import Products from './components/Products.vue'
import Contact from './components/Contact.vue'


export default {
  name: 'App',
  components: {
    Home,
    About,
    Products,
    Contact
  }
}
</script>

<style>
#app {
  
}
</style>
