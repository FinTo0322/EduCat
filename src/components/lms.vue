<template>
   <section>
    <div class="container">
        <div class="row " data-aos="fade-right" data-aos-delay="50" data-aos-duration="1000">
            <div class="col-lg-6">
                <img src="../assets/lms1.png" alt="lms1" class="img-fluid">
                </div>
                <div class="col-xl-4 lms-text">
                    <h1>General Education</h1>
                <p class="text-muted">Transform your learning digitally. Streamline all your school processes in one platform made especially for students, for teachers, and for parents.</p>
                <a href="#" class="text-decoration-none h4 text-primary">Learn more</a>
                </div>
                </div>
            </div>

            <div class="container">
        <div class="row d-flex flex-xl-row-reverse" data-aos="fade-left" data-aos-delay="50" data-aos-duration="1000">
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

   <section class="lms-bg mt-5">
        <div class="container">
            <div class="row">
                <div class="col-xl-4 lms-text-bg">
        <h1 class="ms-5">Designed to help you Work Smarter not Harder</h1>
        <p class="ms-5">Educat LMS offers the perfect end-to-end solution for schools and businesses. It also provides you with all the features needed to make learning and training easier. </p>
        <a href="#" class="btn ms-5">BOOK A DEMO</a>
    </div>
    <div class="col-lg-6 text-center flex-wrap d-none d-xl-flex">
        <div class="text rounded m-5">
            <button class="material-icons btn">signal_cellular_alt</button>
            <p>Progress Monitoring</p>
        </div>
        <div class="text rounded m-5">
            <button class="material-icons btn">signal_cellular_alt</button>
            <p>Progress Monitoring</p>
        </div>
        <div class="text rounded m-5">
            <button class="material-icons btn">signal_cellular_alt</button>
            <p>Progress Monitoring</p>
        </div>
        <div class="text rounded m-5">
            <button class="material-icons btn">signal_cellular_alt</button>
            <p>Progress Monitoring</p>
        </div>
    </div>
            </div>
        </div>
   </section>

   <section class="counter">
    <div class="container justify-content-evenly lh-lg text-center gx-5">
                <div class="row">
                    <div class="col-md-4 mb-5">
                        <h1>1,200</h1>
                        <p>Learning Materials Donated </p>
                    </div>
                    <div class="col-md-4 mb-5">
                        <h1>5,500</h1>
                        <p>LMS Users</p>
                    </div>
                    <div class="col-md-4 mb-5">
                        <h1>3000</h1>
                        <p>Trained Professionals</p>
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

    .lms-bg{
    margin: auto;
    width: 70%;
    height: 30em;
    background-image: url('../assets/bg.png');
    background-size: cover;
    border-radius: 50px;
    overflow: hidden;
  }

  .lms-bg a{
    background-color: #3966D8;
    color:white;
    border:none;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
  }

  .material-icons{
    font-size: 80px;
    color: #7BC144;
  }

  .lms-text-bg{
    margin: 3em 5em;
  }

  .text{
    margin:auto;
    width: 25%;
    background-color: white;
  }

  .counter h1{
    color: #7BC144;
    font-weight: 700;
    font-size: 48px;
  }

  .counter p{
    font-weight: 400;
    font-size: 18px;
    line-height: 32px;
  }


  @media screen and (max-width: 1025px ) {
    .lms-text-bg{
    margin: 8em auto;
  }
  }

  </style>
  