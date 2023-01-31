<template>
    <!-- Product section -->
    <section id="product">
        <div class="text-center">
            <h4 class="text-muted" style="letter-spacing: 10px;">OUR PRODUCTS</h4>
            <h1 class="fs-1">Learn without limits</h1>
        </div>
            <div class="container justify-content-evenly lh-lg text-center gx-5">
                <div class="row">
                    <div class="col-md-4">
                        <img src="../assets/product1.svg" alt="product1" class="img-fluid">
                        <h3>Educat LMS</h3>
                        <p>A Learning Management System and content library that offers a variety of ways on how to learn through blended learning.</p>
                    </div>
                    <div class="col-md-4">
                        <img src="../assets/product1.svg" alt="product1" class="img-fluid">
                        <h3>Educat Library</h3>
                        <p>An online library that contains Digital Modules, Worksheets and Assessments aligned with DepEd’s K to 12 Curriculum</p>
                    </div>
                    <div class="col-md-4">
                        <img src="../assets/product1.svg" alt="product1" class="img-fluid">
                        <h3>Educat Rover</h3>
                        <p>An offline solution run by mini-computers that are equipped with wireless local area network for contactless file transfers.</p>
                    </div>
                </div>
            </div>
    </section>

<!-- features -->


    
    <section class="feature d-none d-xxl-block">
        <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false">
            <div class="features">
        <h1 class="text-white" >Do more with Educat</h1>
    </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="../assets/feature1.png" class="float-end" alt="feature1">
      <h1 class="">01 <small>Offline learning</small></h1>
        <p>The ideal solution to empower learners with no access to an internet connection.</p>
    </div>
    <div class="carousel-item">
      <img src="../assets/feature2.png" class="float-end" alt="feature2">
      <h1 class="">02 <small>Supplementary Learning Materials</small></h1>
        <p>Our printed and interactive learning materials are perfect to help strengthen your learning.</p>
    </div>
    <div class="carousel-item">
      <img src="../assets/feature3.png" class="float-end" alt="feature3">
      <h1 class="">03 <small>All-in-one LMS Platform</small></h1>
        <p>All the solutions you nedd in one powerful platform.</p>
    </div>
  </div>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

</section>
  </template>
  
  <script>
  export default {
    name: 'productPage',
  
  }
  
  // alert nav
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>

  #product, .container{
    margin-top: 8em;
    margin-bottom: 10em;
  }

  h3{
    margin-top: 2em;
  }
    
  .feature{
    margin: auto;
    width: 70%;
    height: 30em;
    background-color: #3966D8;
    border-radius: 50px;
    overflow: hidden;
    color:white;
  }

  .feature img{
    margin-right:1em;
    padding-right: 3em;
    width: 50%;
  }

  .features{
    margin-top:3em; width: 20%; margin-left: 5em; z-index: -1;
    font-weight: 800;
  }

  .features h1{
    font-size: 45px;
    font-weight: 800;
  }


  .carousel-inner h1{
    width: 40%;
    margin-top: 3em;
    margin-left: 1em;
    font-size: 45px;
    font-weight: 800;
  }

  .carousel-inner small{
    width: 30%;
    margin-top: 3em;
    margin-left: 1em;
    font-size: 20px;
    font-weight:bold;
  }
  .carousel-inner p{
    width: 30%;
    margin-left: 8em;
  }

  </style>
  