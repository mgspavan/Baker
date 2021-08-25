<template>
  
      <div  id = "about-link" class="about-us-container">
        <div class = "title">
        <br>
        <br>
        <br>
        <h6>ABOUT US</h6>
    <h2>Meet the history of our <span style="color :#c98d83 "> company </span></h2>
      <p>Curabitur sed iaculis dolor - non congue ligula mi ut laoreet mollis.</p>
        </div>
        
        <br>
        <br>
        <br>
    <div class="row-about">
  <div class="column">
    <div class="card">
    <!--<img src="../assets/baker3-home-pic1.png" alt=""> -->
    <div class="column_attr clearfix align_center bg-contain" style="background-image:url('https://themes.muffingroup.com/be/baker3/wp-content/uploads/2021/03/baker3-wrap-bg2.png');background-repeat:no-repeat;background-position:center;"><div class="google_font" style="font-family:'Playfair Display';font-size:70px;line-height:70px;font-weight:700;letter-spacing:0px;color:#ffc4c4;">1850</div></div>
    
    <div class="column_attr clearfix align_center" style=""><p style="color:#ffffff;">Vivamus in diam turpis. In condimentum maximus <br>pellentesque a aliquam.</p></div>
    

    </div>
  </div>

  <div class="column">
    <div class="card">
    <!--   <img src="../assets/baker3-home-pic2.png" alt=""> -->
<div class="column_attr clearfix align_center bg-contain" style="background-image:url('https://themes.muffingroup.com/be/baker3/wp-content/uploads/2021/03/baker3-wrap-bg2.png');background-repeat:no-repeat;background-position:center;"><div class="google_font" style="font-family:'Playfair Display';font-size:70px;line-height:70px;font-weight:700;letter-spacing:0px;color:#ffc4c4;">1897</div></div>
    <div class="column_attr clearfix align_center" style=""><p style="color:#ffffff;">Duis dignissim mi ut laoreet <br>mollis tellus finibus magnis<br> dis parturient.</p></div>

    </div>
  </div>
  <div class="column">
    <div class="card">
    <!-- <img src="../assets/baker3-home-pic3.png" alt=""> -->
<div class="column_attr clearfix align_center 
bg-contain" 
style="background-image:url('https://themes.muffingroup.com/be/baker3/wp-content/uploads/2021/03/baker3-wrap-bg2.png');
background-repeat:no-repeat;
background-position:center;">

<div class="google_font" 
style="font-family:'Playfair Display';
font-size:70px;line-height:70px;
font-weight:700;
letter-spacing:0px;
color:#ffc4c4;">1951</div></div>


    <div class="column_attr clearfix align_center" 
    style=""><p style="color:#ffffff;">Maecenas mi tortor, <br> pellentesque a aliquam ut, <br> fringilla montes, nascetur.</p></div>
    </div>
  </div>
  <div class="column">
    <div class="card">
   <!-- <img src="../assets/baker3-home-pic4.png" alt=""> -->
   <div class="column_attr clearfix align_center bg-contain" 
   style="background-image:url('https://themes.muffingroup.com/be/baker3/wp-content/uploads/2021/03/baker3-wrap-bg2.png');
   background-repeat:no-repeat;background-position:center;">
   
   <div class="google_font" 
   style="font-family:'Playfair Display';
   font-size:70px;line-height:70px;
   font-weight:700;letter-spacing:0px;
   color:#ffc4c4;">2011</div>  </div>


   <div class="column_attr clearfix align_center" 
   style=""><p style="color:#ffffff;">Maecenas mi tortor, <br> pellentesque a aliquam ut,<br> fringilla montes, nascetur.</p></div>  
      
       


    </div>
  </div>
</div>



<div class = "about-images">
<img src="../assets/baker3-home-pic5.png" alt="">

</div>
       </div>
  
</template>

<script>
export default {
 name : 'About'
}
</script>

<style scoped>


*, *::before, *::after {
    box-sizing: inherit;
    -webkit-font-smoothing: antialiased;
}


.about-us-container{
    background-image: url('../assets/baker3-section-bg1.jpg');
    height:130vh;
    width:100vw;
    margin-top: 0px;
    margin-bottom: 100px;

}
.about-us-container img {
  max-width:100%;
  height: auto;
  margin: 0px;
}



.title  h6{
  color:#F5F5F5;
  font-family: "Inter", Arial, Helvetica, sans-serif;
  text-align: center;
  font-size: 1rem;
 letter-spacing: 1px;
 
  
}

.title h2{

    font-size: 70px;
    line-height: 80px;
    font-weight: 900;
    letter-spacing: 0px;
    font-family: "Playfair Display";
    color: #FFFFFF;
    text-align: center;
    margin-top: 10px;
    vertical-align: baseline;
} 

.title p {
  color:#F5F5F5;
  margin : 0 0 15px;
  text-align: center;
   display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    letter-spacing: 0.5px;
    font-size: 18px;

}

 /* Float four columns side by side */
.column {
  float: left;
  width: 21%;
  padding: 0 20px;
}

/* Remove extra left and right margins, due to padding in columns */
.row-about {
  margin: 0px -5px;
  margin-bottom: 250px;
  background-image: url('../assets/baker3-section-bg1.jpg');
 
  }



/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
 
  padding: 15px;
  text-align: center;
  
}

.card h3{
  font-family: 'Playfair Display',Arial,Tahoma,sans-serif;
    font-size: 70px;
    line-height: 70px;
    font-weight: 700;
    letter-spacing: 0px;
    color: #ffc4c4;
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

.clearfix:before, .clearfix:after {
    content: '\0020';
    display: block;
    overflow: hidden;
    visibility: hidden;
    width: 0;
    height: 0;
}

.bg-contain{
  background-size: contain;
}
.column_attr.align_center {
    text-align: center;
}

.about-images {
  align-items: center;
  
  
}

.about-images img{
  margin-left :6%;
  width: 85%;
  margin-bottom:50px;
  margin-top : 80px;
}




</style>