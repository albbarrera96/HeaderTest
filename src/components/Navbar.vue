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

        max-width: 1440px;
        height: 40px;
        left: 0px;      
        height: 40px;
        margin-left: 300px;
        top: 170px;
        font: 'Nunito Sans' ; 
        font-style: normal;
        /*font-size: 14px;
        line-height: 19px; */
        display: flex;
        align-items: center;
        text-transform: uppercase; 
    }
    .nav-link:hover{
        color: rgba(43, 172, 227, 1);
        font-weight: bold;
    }
    .nav-link {
        color: black;
        font-size: 14px;
        margin-right: 20px
        
    }

</style>
