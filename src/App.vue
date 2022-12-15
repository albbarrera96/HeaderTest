<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Nav from './components/Navbar.vue'
</script>

<template>
<div class="main">
  <div class="row" style="margin-bottom" id="TopHeader">
    <div class="col-lg-9" style="margin-top:20px">
      <div class="d-flex flex-row">
        <div style="padding-top:10px"><img src="./assets/tireb.png"></div>
        <div class="fw-bold" style="padding-top:20px"><h2>(905) 793-1881</h2></div>
      </div>  
    </div>
    <div class="col-lg-3">
      <div class="bg-light" id="cartInfo">
        <p>DYNAMIC MOTOR SPORTS INC</p>
        <small class="text-primary">View Account  |  SIGN OUT</small>
        <div class="d-grid gap-2 mt-1">
          <button class="btn btn-success" style="margin-bottom:10px">VIEW CART ()</button>
        </div>
      </div>
    </div>
  </div>
</div>
  <Nav />

  <RouterView />
</template>

<style scoped>
  .main{
    padding-right:20px;
    margin-bottom: 15px;
  }
  #cartInfo{
    border-radius: 4px;
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 10px;
    font-size: 14px;
  }

</style>
