<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Nav from './components/Navbar.vue'
</script>

<template>
  <!--------XXL Breakpoint---------->
  <div class="d-none d-xxl-block">
    <div class="main">
      <div class="row" id="TopHeader">
        <div class="col-lg-9">
          <div class="d-flex flex-row">
            <div style="margin-top:40px"><img src="./assets/tireb.png"></div>
            <div class="fw-bold" style="margin-top:50px; margin-left:20px"><h2>(905) 793-1881</h2></div>
          </div>  
        </div>
        <div class="col-lg-3">
          <div class="bg-light" id="cartInfo" style="margin-top:20px">
            <p style="padding-top:20px">DYNAMIC MOTOR SPORTS INC</p>
            <p class="text-primary" style="font-size:12px; margin-bottom:20px">View Account  |  SIGN OUT</p>
            <div class="d-grid gap-2 mt-1">
              <button class="btn btn-success" style="margin-bottom:20px">VIEW CART (1)</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-----XL Breakpoint ------>
  <div class="main d-none d-xl-block d-xxl-none d-lg-block">
    <div class="row" style="margin-bottom" id="TopHeader">
      <div class="col-lg-9" style="margin-top:50px">
        <div class="d-flex flex-row">
          <div><img src="./assets/tireb.png"></div>
          <div class="fw-bold" style="margin-top:10px"><h2>(905) 793-1881</h2></div>
        </div>  
      </div>
      <div class="col-lg-3" style="margin-top:20px">
        <div class="bg-light" id="cartInfo">
          <p style="padding-top:20px">DYNAMIC MOTOR SPORTS INC</p>
          <p class="text-primary" style="margin-bottom:20px">View Account  |  SIGN OUT</p>
          <div class="d-grid gap-2 mt-1">
            <button class="btn btn-success" style="margin-bottom:20px">VIEW CART (1)</button>
          </div>
        </div>
        ESTE ES XL
      </div>
    </div>
  </div>
  <Nav />
  <!--------MD Breakpoint-------->
  <div class="d-none d-md-block d-sm-block d-lg-none">
    <div class="col-md-6 col-sm-8">
        <div class="d-flex flex-row mx-2 px-2">
          <div style="margin-top:10px"><img src="./assets/tireb.png"></div>
          <div class="fw-bold" style="padding-top:20px"><h2>(905) 793-1881</h2></div>
          ESTE ES EL MD
        </div>  
    </div>
      <div class="col-lg-3">
        <div class="bg-light" id="cartInfo">
          <p style="padding-top:20px">DYNAMIC MOTOR SPORTS INC</p>
          <small class="text-primary">View Account  |  SIGN OUT</small>
          <div class="d-grid gap-2 mt-1">
            <button class="btn btn-success" style="margin-bottom:10px">VIEW CART (1)</button>
          </div>
        </div>
      </div>
  </div>
  <!-------SM Breakpoint---------->
    <div class="d-block d-sm-none" style="margin-top:20px">
      <div class="col-12 mx-4">
        <div class="d-flex flex-row">
          <div style="padding-top:10px"><img src="./assets/tireb.png"></div>
          <div class="fw-bold ms-5" style="padding-top:20px"><h2>(905) 793-1881</h2></div>
          ESTE ES EL SM
        </div>
      </div>

      <div class="col-12 px-4">
        <div class="bg-light" id="cartInfo">
          <p style="padding-top:20px">DYNAMIC MOTOR SPORTS INC</p>
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
    font-size: 14px;
  }

</style>
