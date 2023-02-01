<template>
    <section class="socials">
        <div class="d-flex justify-content-center mt-5">
          <i class="fa-brands fa-square-facebook"></i>
          <i class="fa-brands fa-instagram ms-5"></i>
          <i class="fa-brands fa-twitter ms-5"></i>
          <img src="../assets/pci-social.png" alt="pci social" class="ms-5">

        </div>
    </section>

    <footer>
      <div class="navbar justify-content-evenly">
      <img src="../assets/logo.png" alt="logo">
      <p class="mt-3">© Copyright 2021. All rights reserved.</p>
      <ul class="nav ">
      <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About Us</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Products</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Shop</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Terms of Use</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Data Privacy</a>
      </li>
    </ul> 
  </div>
    </footer>
</template>
       
       <script>
       export default {
         name: 'footerPage',
       
       }
       
       // alert nav
       </script>
       
       <!-- Add "scoped" attribute to limit CSS to this component only -->
       <style scoped>
          .socials{
            margin-top: 5em;
            margin-bottom: 5em;
          }

          i{
            color: #3966D8;
            font-size:30px;
          }
       </style>
       