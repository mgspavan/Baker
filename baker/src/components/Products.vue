<template>
  <div id = "product-link" class="products-page">
    <div class="products-container"></div>
    <div class="products-header">
      <h3>WHAT WE PRODUCE ?</h3>
      <h1>
        Meet our original products made<br />
        with love
      </h1>
    </div>
  
     <div class="row-about">
  <div class="column">
    <div class="card">
    <img src="../assets/baker3-products-pic2.png" alt="">

    <h3>Wheat cookies </h3>
    <p style="color :#783b31 ">250g</p>
    <p>Duis vehicula, enim vel fermentum porta, augue enim ullamcorper metus, vel pellentesque libero est sit amet velit. Nullam sit amet velit dictum, vehicula purus ac, posuere nibh. Proin maximus maximus odio..</p>
    
      <ul class = "wheat-list">
     <li>Dolor sit amet, consetetur</li>
     <li>Sadipscing elitr, sed velit dictum pellentesque</li>
     <li>Diam nonumy eirmod ullamcorper metus</li>
      </ul>
  <button class="btn-wheat">SEE FULL PRODUCT INFO</button>
    </div>
  </div>

  <div class="column">
    <div class="card">
    <img src="../assets/baker3-products-pic3.png" alt="">

    <h3 style="color : #7cb2b7"> Sesame cookies </h3>
    <p style="color : #7cb2b7">230g</p>
    <p>Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat accumsan et iusto odio dignissim.</p>
      
    <ul class = "sesame-list">

     <li>Nonummy nibh euismod tincidunt ut laoreet </li>
     <li>Dolore magna aliquam erat volutpat</li>
     <li>Ullamcorper suscipit lobortis nisl ut aliquip</li>
    </ul>

    <button class="btn-sesame">SEE FULL PRODUCT INFO</button>

    </div>
  </div>
  
  
</div>
    
    </div>

</template>

<script>
export default {
data (){
  return{

   

    
  }
}


};
</script>

<style scoped>



.products-page {
height:100vh;
width:100vw;
margin-top: 50px;
padding-top:70px;
padding-bottom:70px;


}
.products-container {
  margin-top: 80px;
  margin-bottom: 100px;
}

.products-header {
  margin-top: 30px;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: #ffc4c4;
  font-size: 14px;
  padding: 20px;
}
.products-header h1 {
  margin-top: 30px;
  margin-bottom: 10px;
  font-family: playfair Display;
  color: #783b31;
  font-size: 52px;
  text-align: center;
}


.row-about{
margin-top:0px;
}
.column {
  float: left;
  width: 35%;
  padding: 30px;
  margin: 10px 65px;
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
  margin-top:40px;
  color: #783b31;
  font-size: 45px;
  font-family: 'playfair Display';
  
}

.card p{
 color: #555162;
 font-family: Arial, Helvetica, sans-serif;
 font-size: 16px;
 margin-top: 25px;
 
}

.card img{
  max-width:100%;
  height:auto;
}
.btn-wheat{
font-family: "Inter";
font-size: 14px;
line-height: 14px;
font-weight:300;
letter-spacing : 3px;
padding: 18px 40px 18px 40px;
border-radius : 25px;
margin:15px;
vertical-align:middle;
background-color: #471e1e;
color:#ffffff;
text-align: center;
margin-bottom:100px;
} 
  
.btn-sesame{
font-family: "Inter";
font-size: 14px;
line-height: 14px;
font-weight:300;
letter-spacing : 3px;
padding: 18px 40px 18px 40px;
border-radius : 25px;
margin:15px;
vertical-align:middle;
background-color: #7cb2b7;
color : #ffffff;
text-align:center;
margin-bottom:100px;
} 






/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}


@media only screen and (min-width:1025px) and (max-width: 1201px){

  .column {
    width:30%;
   
  }
  


}



</style>
