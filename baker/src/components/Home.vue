<template>
  <div class="hello">
    <div>
      <nav class = "container"> 
      <div class = "logo"><img  src="../assets/retina-baker3.png"></div>
   
    <a  class= "item" href="">Home</a>
    <a class = "item" href="">Products</a>
    <a class = "item" href="">About</a>
    <a class = "item" href="">Contact</a>
</nav>
</div>
    
<div class = "heading">
<h1>Taste the <br> original  <span style = "color:#783B31"> cookies  </span></h1>

</div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello{
  background-color:#773a31b4;
  width : 100vw;
  height:100vh;
  
}

.container{
  margin-top: 0px;
  display:flex;
  justify-content:space-around;
  align-items: center;
  background-color: ;
  box-shadow: 0 5px 15px -10p;
  max-height: 80px;
  margin:0
}
.item  {
  color:white;
  text-decoration:none;
  font-family:sans-serif;
  padding:24px;
}

.item:nth-of-type(n+3){
  order:2;
}
.logo{
  order:1;
  padding:1rem;
  height :80px;pu
  width:200px;
  margin-top: 20px;
  }

  .logo img{
    max-height:100%;
    max-width:100%;
}

.heading {
 margin-left:auto;
 max-height:120px;
 
 
}

.heading h1{
  margin-top: 80px;
  vertical-align: middle;
  font-family: playfair Display;
  font-size: 70px;
  color:white;
}
</style>
