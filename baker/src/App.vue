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
@media only screen and (min-width:768px) and (max-width:1024px){
  *{
    max-width:100%;
    height:auto;
  }


}


@media only screen and (min-width:481px) and (max-width:768px){
  *{
    max-width:100%;
    height:auto;
  }

  
}

@media only screen and (min-width:320px) and (max-width:480px){
  *{
    max-width:100%;
    height:auto;
  }

  
}

</style>
