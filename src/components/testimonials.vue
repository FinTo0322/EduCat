<template>

<section class="testimonials">
    <div class="container">
        <div class="row">
            <div class="col-lg-6">
                <h1>They Said It First</h1>
        <p class="mt-5">Scuola Maria is fortunate to work with PCI early on when the pandemic hit the country. My ideas and my curriculum design all came to life in the NEST — our exclusive LMS for our students. If not for PCI, we wouldn't be able to continue education at this very difficult time.
</p>
        <dt class="mt-5 ">Ina Gonda-Ramos, MAE-CDE, LPT </dt>
        <dd>Program Director of Scuola Maria</dd>
            </div>
            <div class="col-lg-6">
                <img src="../assets/testimonial.png" alt="testimonial" class="img-fluid">
            </div>
        </div>
    </div>
</section>

<section class="partners text-center mt-5">
    <h5 class="text-muted">OUR HAPPY CLIENTS</h5>
    <h1>Our Partners</h1>
    <div class="d-lg-flex justify-content-center">
        <img src="../assets/Partners/partner1.png" alt="partner 1" class="ms-5"/>
        <img src="../assets/Partners/partner2.png" alt="partner 2" class="ms-5"/>
        <img src="../assets/Partners/partner4.png" alt="partner 3" class="ms-5"/>
        <img src="../assets/Partners/partner3.png" alt="partner 4" class="ms-5"/>
        <img src="../assets/Partners/partner5.png" alt="partner 5" class="ms-5"/>
        <img src="../assets/Partners/partner6.png" alt="partner 6" class="ms-5"/>
    </div>
</section>

<section class="d-flex justify-content-center">
    <div class="CTA">
        <img src="../assets/cat.svg" alt="cat" class="mt-5 mx-5">
        <div class="text-center mt-3">
            <h1>Want to see what Educat can do for you?</h1>
            <p>Learn more by booking a demo today and discover why Educat is the only platform you'll ever need for your learning and training needs.</p>
            <a href="#" class="btn text-center">LET'S TALK!</a>
        </div>
        <img src="../assets/paws.svg" alt="paws"  class="mt-5 mx-5 pt-5">
    </div>
</section>
   </template>
   
   <script>
   export default {
     name: 'testimonialsPage',
   
   }
   
   // alert nav
   </script>
   
   <!-- Add "scoped" attribute to limit CSS to this component only -->
   <style scoped>
        .testimonials{
            margin-top: 5em;
            background-image: url('../assets/testi-bg.png');
            background-size: cover;
            margin: auto;
            width: 100%;
            height: auto;
            overflow: hidden;
            background-position: right 25% bottom 60%;
        }

        .testimonials h1{
            margin-top: 1em;
            font-weight: 700;
            font-size: 50px;
        }

        .testimonials p{
            font-weight: 400;
            font-size: 18px;
        }
        .testimonials img{
            margin-left: 18em;
        }

        .partners{
            margin-top: 5em;
            font-weight: 700;
            font-size: 20px;
            letter-spacing: 0.165em;
        }

        .partners img{
            margin-top: 5em;
            filter: grayscale(100%);
        }

        .partners img:hover{
            filter: grayscale(0%);
        }

        .CTA{
            display: flex;
            margin-top: 10em;
            width: 60%;
            background-color: #3966D8;
            color:white;
            border-radius: 20px;
            font-size: 16px;
        }

        .CTA a{
            background-color: white;
            color:#3966D8;
            border:none;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            font-size: 16px;
        }

        @media screen and (max-width: 560px) {
            .testimonials img{
                margin-left: 0;
            }
        }
   </style>
   