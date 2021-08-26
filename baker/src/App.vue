<template>
 <div>
  <Home />
  <About/>
  <Products/>
  <Contact/>
  <Footer/>
 </div>
</template>

<script>
import About from './components/About.vue'
import Home from './components/Home.vue'
import Products from './components/Products.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Home,
    About,
    Products,
    Contact,
    Footer
  }
}
</script>

<style>

</style>
