<template>

    <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav" id="navbar-wrapper">
                <li class="nav-item">
                    <a href="#" class="nav-link">HOME</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">VEHICLE</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">TIRES</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">WHEELS</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">HARDWARE</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">CALCULATORS</a>
                </li>                                
                <li class="nav-item">
                    <a href="#" class="nav-link">ACCOUNT</a>
                </li>                                
            </ul>
        </div>
    </div>
    </nav>

</template>

<script setup>

</script>

<style scoped>
    .navbar-nav {
        position: absolute;
        width: 1440px;
        height: 40px;
        left: 0px;
        top: 170px;
        background: #F6F6F6;        
        width: 1440px;
        height: 40px;
        left: 0px;
        top: 170px;
        font: 'Nunito Sans' ;
        font-style: normal;
        font-weight: 900px;
        font-size: 14px;
        line-height: 19px;
        display: flex;
        align-items: center;
        text-align: center;
        text-transform: uppercase;
    }
    .nav-link:hover{
        color: rgba(43, 172, 227, 1);
        font-weight: bold;
    }

</style>
