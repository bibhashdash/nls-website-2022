<template>
    <div class="navbar-container">
        <div class="menu-icon-container bigscreen-hidden">
            <img class="menu-icon" src="../assets/images/hamburger.svg" alt="">
        </div>
        <div class="navlinks">

        
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/about">About</NuxtLink>
        <NuxtLink to="/activities">Activities</NuxtLink>
        <NuxtLink to="/donate">Donate</NuxtLink>
        <NuxtLink to="/news">News</NuxtLink>
        <NuxtLink to="/volunteer">Volunteer</NuxtLink>
        </div>
    </div>
</template>

<script>
export default {
    name: "Navbar",
    
}
</script>

<style>
.bigscreen-hidden {
    display: none;
}
.navbar-container {
    width: 90%;
    max-width: 992px;
    border: 1px solid rgb(32, 95, 51);
    
}
.navlinks {
display: flex;
    justify-content: space-evenly;
}
.menu-icon {
    width: 60px;
    height: 60px;
}
@media only screen and (max-width: 576px) {

}
</style>