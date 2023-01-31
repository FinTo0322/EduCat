<template>
  <!-- Hero Section -->
  
  <div class="container mt-5">
    <div class="row">
      <div class="col-lg-6">
        <div class="hero-text">
          <h1>The LMS that's built for your needs</h1>
          <p>Experience seamless communication, easy data migration, and secured user management in one awesome platform.</p>
          <a class="btn">GO TO LMS PORTAL</a>
        </div>
      </div>
      <div class=" col-lg-6 mt-2 d-none d-lg-block mt-5">
        <!--  -->
          <img src="../assets/hero-banner.png" alt="" class="img-fluid"/>
        </div>
      </div>
    </div>

  <div class=" justify-content-center mb-5 d-none d-lg-flex">        
          <a href="#product" class="btn btn-success btn-lg down-button">
          <i class="fa-solid fa-chevron-down fs-1 text-center my-3"></i>
          </a>
      </div>
  
</template>

<script>
export default {
  name: 'heroPage',

}

// alert nav
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hero-text{
  margin-top: 10em;
  font-style: normal;
} 

 .hero-text h1{
  width: 500px;
  font-family: 'Poppins';
  font-weight: 800;
  font-size: 55px;
 }

 .hero-text p{
  font-style: normal;
  font-weight: 400;
  font-size: 22px;
  line-height: 118.92%;
 }

 .hero-text a{
    background-color: #3966D8;
    color:white;
    border:none;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
  }

  @media screen and (max-width:980px ) {
  .hero-text{
  margin-top: 5em;
  text-align: center;
} 

 .hero-text h1{
  width: 100%;
 }
  }

  .down-button{
  height: 100px;
  width: 100px;
  border-radius: 50%;
  }
</style>
