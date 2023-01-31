<template>
<div class="alert alert-primary d-flex align-items-center justify-content-center">
    <small class="nav-link">Covid 19 Response: No one left behind: <a href="#" class="text-decoration-none"> Check out our different ways of helping schools and institutions during the pandemic.➡️</a></small>
  </div>

<nav class="navbar navbar-expand-xl d-flex">
  <div class="container">
    <img src="./assets/logo.png" alt="Logo" class="navbar-brand"/>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarTogglerDemo02">
      <ul class="navbar-nav fs-4">
        <li class="nav-item mx-3">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item mx-3">
          <a class="nav-link" href="#">About Us</a>
        </li>
        <li class="nav-item dropdown mx-3">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" >
            Products
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item mx-3" href="#">Educat LMS</a></li>
            <li><a class="dropdown-item mx-3" href="#">Educat Library</a></li>
            <li><a class="dropdown-item mx-3" href="#">Educat Rover</a></li>
          </ul>
        </li>
        <li class="nav-item mx-3">
          <a class="nav-link" href="#">Blogs</a>
        </li>
        <li class="nav-item mx-3">
          <a class="nav-link" href="#">Contact</a>
        </li>
        <li class="nav-item mx-3">
          <button href="#" class="nav-button">BOOK A DEMO</button>
        </li>
      </ul>
    </div>
  </div>
</nav>
  <hero/>
  <product/>
  <lms/>
</template>

<script>
import hero from './components/hero.vue'
import product from './components/product.vue'
import lms from './components/lms.vue'

export default {
  name: 'App',
  components: {
    hero,
    product,
    lms
  }
}
</script>

<style>
  .nav-button{
    background-color: #7BC144;
    color:white;
    border:none;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
  }
</style>
