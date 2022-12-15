<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Nav from './components/Navbar.vue'
</script>

<template>
  <div class="main d-none d-xl-block d-xxl-none d-lg-block">
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
            <button class="btn btn-success" style="margin-bottom:10px">VIEW CART (1)</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <Nav />
  <div class="d-none d-md-block d-sm-block d-lg-none">
    <div class="col-md-6 col-sm-8">
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
            <button class="btn btn-success" style="margin-bottom:10px">VIEW CART (1)</button>
          </div>
        </div>
      </div>

  </div>
    <div class="d-block d-sm-none">
      <div class="col-12 px-4">
        <div class="d-flex flex-row">
          <div style="padding-top:10px"><img src="./assets/tireb.png"></div>
          <div class="fw-bold ms-5" style="padding-top:20px"><h2>(905) 793-1881</h2></div>
        </div>
      </div>

      <div class="col-12 px-4">
        <div class="bg-light" id="cartInfo">
          <p>DYNAMIC MOTOR SPORTS INC</p>
          <small class="text-primary">View Account  |  SIGN OUT</small>
          <div class="d-grid gap-2 mt-1">
            <button class="btn btn-success" style="margin-bottom:10px">VIEW CART (1)</button>
          </div>
        </div>
      </div>

  </div>

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
