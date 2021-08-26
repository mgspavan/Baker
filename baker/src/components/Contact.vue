<template>
  <div id  = "contact-link">

  <div class = "contact-container">
    <h6>MORE PRODUCTS</h6>
    
    <h2>Our speciality - <br> traditional <br> donuts!</h2>

   <p>Mauris rhoncus orci in imperdiet placerat. Vestibulum euismod nisl <br> suscipit ligula volutpat, a feugiat urna maximus. Cras massa nibh, <br>tincidunt ut eros a, vulputate consequat odio.</p>

   <button class = "contact-btn"> CONTACT US</button>
  </div>

   
 </div>
</template>


<script>
export default {

}
</script>

<style>

.contact-container{
    height: 90vh;
    margin-top:500px;
    padding-top:160px;
    padding-bottom:170px;
    background-color:#fec2c2;
    background-image: url('../assets/baker3-sectionbg2.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    position: relative;
    font-size: 100%;
}

.contact-container h6 {
  color : #F5F5F5;
  font-size:15px;
  line-height:25px;
  font-weight:500;
  letter-spacing:2px;
  font-family : "Inter",Arial, Helvetica, sans-serif;
  margin-bottom:15px;
  text-align: center;
}


.contact-container h2{
    color:#783b31;
    font-size :72px;
    line-height:80px;
    font-weight:900;
    font-family: "playfair Display";
    margin-bottom: 15px;
    text-align: center;

}

.contact-container p {
  color:whitesmoke;
  text-align:center;
  font-size: 1.3rem;
}

.contact-btn {
  color:#ffffff;
  background-color: #783b31;
  border-color:transparent;
  font-family :"Inter", Arial, Helvetica, sans-serif;
  font-size:20px;
  line-height:14px;
  font-weight:600;
  letter-spacing: 5px;
  padding:20px;
  border-width:0px;
  border-radius:45px;
  margin-top:65px;
  margin-left: 29%;
  vertical-align: middle;
  width:38%;
  text-align: center;
  box-sizing:border-box;
}

.contact-footer{
  vertical-align: baseline;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 33%;
  padding: 20px;
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
  font-size: 24px;
  font-family: 'playfair Display';
  
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

 .contact-container h6 {
   margin-top: 10px;
 }

 .contact-container{
   margin-top:600px;
   
 }
}


</style>