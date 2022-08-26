<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import Menu from './components/Menu.vue'
</script>

<template>

  <header>
    <div class="container2">
    <nav class="navbar "  >
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="src/assets/logo.svg" alt="" width="30" height="24" class="d-inline-block align-text-top">
      Vue Js
    </a>
      <ul class="nav-right">
      <li>
         <RouterLink to="/">Personal</RouterLink>
      </li>
      <li><RouterLink to="/about">Skill</RouterLink></li>
    </ul>
  
  </div>
</nav>
  </div>

<div >
  <RouterView />
</div>
  </header>


  </template>

  <style scoped>


  
  .navbar {
    
    /* padding-right:100px ; */
    margin-top: -300px;
    margin-left: -350px;
    width: 1918px;
    height: 80px;
    background-color: slateblue;
  }

  .nav-right {
    display: flex;
    gap: 2rem;
    list-style: none;
    padding-right: 50px;
  }

  .nav-right  a{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 25px;
    color: white;
    text-decoration: none;
  }
  
  </style>