<template>
<div class=" header">
  <div class="home">
   
    <div class="container">
   <div class="logo"><img src="../assets/retina-baker3.png" alt=""></div>
   <a href="#1" class="item">Home</a>
   <a href="#2" class="item">Products</a>
   <a href="#3" class="item">About</a>
   <a href="#4" class="item">Contact</a>
   
</div>

<div class="main">  
   <div class =  main-left><img src="../assets/baker3-slider-icon1.png" alt=""></div> 
  <div class = "header-title-container">
    <h1 class = "header-title">  Taste the <br> original <span>cookies</span> </h1> 
    </div>                  
    
     <div main-right><img src="../assets/baker3-.png" alt=""></div>
    
     </div >

     <div class="btn-main"><a  href="">L E A R N  M O R E</a></div>
      
      
 <div class="header-image-container">

   <img src="../assets/baker3-slider-pic1.png" alt="">

 </div>
 </div>

<div class = "produce" >
  <div class = "produce-header">
<h3>WHAT WE PRODUCE ?</h3>
<h1>only original recipes  made <br> with tradition</h1>

  </div>
 


<div class="row">
  <div class="column">
    <div class="card">
    <img src="../assets/baker3-home-pic1.png" alt="">

    <h3>Chocolate <br> cookies</h3>
    <p>Lorem ipsum dolor sit amet, <br>consectetur adipiscing elit<br> natoque penatibus.</p>

    </div>
  </div>

  <div class="column">
    <div class="card">
    <img src="../assets/baker3-home-pic2.png" alt="">

    <h3> Legendary Wheat <br> biscuits</h3>
    <p>Sed ultrices nisl velit, <br>eu ornare est ullamcorper<br> eget arcu venenatis.</p>

    </div>
  </div>
  <div class="column">
    <div class="card">
    <img src="../assets/baker3-home-pic3.png" alt="">

     <h3>Grandma's recipe <br> pretzels</h3>
    <p>Nunc quis nibh magna. <br>Proin risus erat, fringilla<br> tellus finibus, eleifend.</p>

    </div>
  </div>
  <div class="column">
    <div class="card">
    <img src="../assets/baker3-home-pic4.png" alt="">
      <h3>Sweet french fresh <br> pastries</h3>
      
       <p>Curabitur ut tortor a orci<br> fermentum ultricies mollis<br> lobortis laoreet mollis.</p>


    </div>
  </div>
</div>
<div class="btn-produce"><a  href=""> SEE ALL COOKIES</a></div> 


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



*{
  margin:0;
  padding:0;
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
}

.header{
width: 100vw;

}
.home{
  background-color: #c98d83;
  max-width: 100vw;
  height:90vh;
}


.container {
  margin: 0px;
  display: -webkit-box;
  height:130px;
  line-height:130px;
 
  display: flex;
  justify-content: space-around;
  -webkit-box-align: center;
  align-items: center;
  background: #c98d83;
 
  
}

.logo {
   height:130px;
   width:200px;
  -webkit-box-ordinal-group: 2;
  order: 1;
  border-radius: 100%;
  background: #c98d83;
 
  font-size: 24px;
  color: #fff;
  line-height: 22px;
  padding: 20px;
}

.logo img{
  max-width:100%;
  height:auto;
}
.item {
  color: rgba(255, 255, 255, 0.88);
  text-decoration: none;
  font-family: sans-serif;
  
}
.item:hover{
    color: #fff;
    background: rgba(255, 255, 255, 0.15);
}


.item:nth-of-type(n+3) {
  -webkit-box-ordinal-group: 3;
          order: 2;
}


@media all and (max-width: 800px) {
  .container {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
            flex-direction: column;
    -webkit-box-align: stretch;
            align-items: stretch;
  }
 
  .logo {
    -webkit-box-ordinal-group: 1;
            order: 0;
    text-align: center;
    width: 100px;
    margin: auto auto;
  }
 
  .item {
    text-align: center;
  
  }
}



.main{
  display: flex;
  justify-content: space-around;
  margin-top : 20px;
  padding: 25px;
}
.header-title-container h1{
  flex-grow: 2;
 justify-content: center;
 text-align:center;
 
  
  font-family: playfair Display;
  font-size: 70px;
  color:white;
}
 .header-title span {
   color: #783b31;
 }

.main img{
  vertical-align: middle;
}
main-left img{
  vertical-align: middle;
  margin: 5px;

}

.btn-main {
  position: relative;
  display: block;
  border-radius:25px;
  background-color: #783b31;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  padding: 20px;
  font-weight:bold;
  width:180px;
  height:50px;
  margin: auto;
  font-size: 1rem;
  
 }

 .btn-main , a{
text-decoration: none;
margin:auto;
color: #fff;
font-family: inter;
vertical-align: middle;
text-align: center;
text-align: justify;
 }


.header-image-container{
  padding:0 25px;
  align-items: center;
}
 .header-image-container img{
   max-width: 100%;
   height:auto;
 }


.produce  {
 margin-top: 300px;
 margin-bottom: 100px;
 padding: 20px;

}
 .produce-header{
  
   font-family: Arial, Helvetica, sans-serif;
   text-align: center;
   color: #FFC4C4;
   font-size: 14px;
   padding: 20px;

 }
  .produce-header h1{
    margin-top : 30px;
    margin-bottom:20px;
    font-family: playfair Display;
    color :#783b31;
    font-size: 60px;
  }



/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 10px;
}

/* Remove extra left and right margins, due to padding in columns */
.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
 
  padding: 16px;
  text-align: center;
  
}

.card h3{
  margin-top:48px;
  color: #783b31;
  font-size: 24px;
  font-family: playfair Display;
}

.card p{
 color: #555162;
 font-family: Arial, Helvetica, sans-serif;
 font-size: 16px;
 margin-top: 25px;
 
}

/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

.btn-produce{
  margin-top: 60px;
  margin-left:40%;
 
  position: relative;
  border-radius:25px;
  background-color: #783b31;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  padding: 20px;
  font-weight:bold;
  width:200px;
  height:50px;
  font-size: 0.9rem;
 text-justify: auto;
 vertical-align: middle;
  
}


</style>
