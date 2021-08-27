<template>
  
<div class = "footer-container">

<div class = "contact-footer">

    <div class="row-footer">
  <div class="column">
    <div class="card">
    

    <h4>Envato <br>Level 13, 2 Elizabeth <br>Victoria 3000 <br> Australia</h4>

    </div>
  </div>

  <div class="column">
    <div class="card">
    <img src="../assets/baker3-footer-logo.png" alt="">

<br>
   <br> 
    <p>PLEASE CALL US</p>

     <h3>+61 (0) 3 8376 6284</h3>

    </div>
  </div>
  <div class="column">
    <div class="card">
      
    <ul class = "list">
   
       <li> Our team</li>
       <li> Used products</li>
       <li> Our histoty</li>
       <li> Our clients</li>
       <li> Certificates</li>
    </ul> 
    </div>
  </div>
  
</div>

</div>

<div>
<p class="footer-text">© 2021 Wohlig |  </p>

</div>
  
</div>

</template>

<script>
export default {

}
</script>

<style>

.footer-container{
    height:100vh;
    width:100vw;
}

.contact-footer{
  width:100%;
  height:auto;
  vertical-align: baseline;
}



/* Float four columns side by side */
.column {
  float: left;
  width: 30%;
  padding: 15px;
}

/* Remove extra left and right margins, due to padding in columns */
.row-footer {
  margin-top : 150px;
  margin-bottom: 100px;
  padding:20px;
  }

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
 
  padding: 18px;
  text-align: center;
  
}

.card h3{
  margin-top:40px;
  color: #783b31;
  font-size: 35px;
  font-family: 'playfair Display';
  
}



/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 768px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}


.row-footer .card h4{
  text-align: center;
  font-size: 30px;
  line-height: 30px;
  font-weight: 400;
  font-family: "playfair Display";
  color:#783b31;
}


.row-footer .list li {
  font-size: 18px;
  list-style-type: none;
  margin-top:20px;
  position: relative;
 letter-spacing: 1px;
  padding-left : 50px;
  display: list-item;
  font :"inherit";
  color :#555162;
 
}


.row-footer img{
  max-width:100%;
  height:auto;

}

 .footer-container .footer-text {
   display: block;
  position: absolute;
  font-family: Arial, Helvetica, sans-serif;
  margin-top:400px;
  margin-left:45%;
 
 
}

.row-footer p {
  color: #783b31;
}

@media only screen and (min-width:768px) and (max-width:1024px){

  

.row-footer .column{
  width:18%;
  padding: 50px;
}
.column .card{
  padding: 10px;
  width: 180%;
  padding-left: 0px;
}

}
</style>