<template>
  
  <Home />
  <About/>
</template>

<script>
import About from './components/About.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
    About
  }
}
</script>

<style>
#app {
  
}
</style>
