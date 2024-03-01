<script setup>
    import MenuIcon from './icons/MenuIcon.vue';
</script>

<template>
<header id="page-header" class="bg-light">
    <div class="content-header">

        <div class="d-flex align-items-center">
            <a class="link-fx fs-lg fw-semibold text-dark" href="#">
                <img src="../assets/image/logo 1.png" alt="logo1" class="logo" width="80px"/>
            </a>
        </div>

        <div class="d-flex align-items-center" >
            <div class="d-none d-lg-block" >
                <ul class="nav-main nav-main-horizontal">
                    <li>
                        <a class="nav-main-link" id="a" href="#">
                        <span id="span">SCHEDULES</span>
                        </a>
                    </li>
                    <li>
                        <a class="nav-main-link" id="a" href="javascript:void(0)">
                        <span id="span">GUIDELINES</span>
                        </a>
                    </li>
                    <li>
                        <a class="nav-main-link" id="a" href="javascript:void(0)">
                        <span id="span">ANIMALS</span>
                        </a>
                    </li>
                    <li>
                        <a class="nav-main-link" id="a" href="javascript:void(0)">
                        <span id="span">PLANTS</span>
                        </a>
                    </li>
                    <li>
                        <a class="nav-main-link" id="a" href="/about-us">
                        <span id="span">ABOUT US</span>
                        </a>
                    </li>
                    <li>
                        <button class="btn"><img src="../assets/image/ticket-star.png" alt="" class="b" />GET TICKETS</button>
                    </li>
                    </ul>
            </div>

            <button  type="button" class="btn btn-alt-secondary d-lg-none ms-1 " data-toggle="layout" data-action="#sidebar_toggle">
             <MenuIcon></MenuIcon>  
            </button>
             
        </div>
    </div>
</header>
</template>