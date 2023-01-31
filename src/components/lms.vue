<template>
   <section>
    <div class="container">
        <div class="row ">
            <div class="col-lg-6">
                <img src="../assets/lms1.png" alt="lms1" class="img-fluid">
                </div>
                <div class="col-xl-4 lms-text" data-aos="fade-right">
                    <h1>General Education</h1>
                <p class="text-muted">Transform your learning digitally. Streamline all your school processes in one platform made especially for students, for teachers, and for parents.</p>
                <a href="#" class="text-decoration-none h4 text-primary">Learn more</a>
                </div>
                </div>
            </div>

            <div class="container">
        <div class="row d-flex flex-xl-row-reverse">
            <div class="col-lg-6">
                <img src="../assets/lms2.png" alt="lms1" class="img-fluid">
                </div>
            <div class="col-xl-4 lms-text">
                    <h1>Professional Training</h1>
                <p class="text-muted">Bringing you a platform that provides end to end solution in the training process for your employees, customers, or partners that allows. </p>
                <a href="#" class="text-decoration-none h4 text-primary">Learn more</a>
                </div>

                </div>
            </div>
   </section>
  </template>
  
  <script>
  export default {
    name: 'lmsPage',
  
  }
  
  // alert nav
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
    section{
        margin-top: 10em;
    }

    .lms-text h1{
        font-family:'Poppins';
        font-weight: 700;
        font-size: 35px;
        margin-bottom: 1.5em;
    }

    .lms-text p{
        font-family:'Poppins';
        font-weight: 400;
        font-size: 20px;
    }
    .lms-text{
        margin:auto;
    }
  </style>
  