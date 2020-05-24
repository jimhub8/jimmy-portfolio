<template>
<nav class="navbar-expand-md navbar fixed-top" id="navbar">
    <span class="navbar-menu ml-auto" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" role="button" @click="show_menu = !show_menu">
        <span class="btn-line"></span>
    </span>
    <div class="collapse navbar-collapse order-1 order-lg-0">
        <!-- Navbar menu-->
        <ul class="navbar-nav ml-auto" v-show="show_menu" style="float: right">
            <li class="nav-item">
                <nuxt-link to="about">About</nuxt-link>
            </li>
            <li class="nav-item">
                <nuxt-link to="resume">Resume</nuxt-link>
            </li>
            <li class="nav-item">
                <nuxt-link to="portfolio">Portfolio</nuxt-link>
            </li>
            <li class="nav-item">
                <nuxt-link to="contact">Contact</nuxt-link>
            </li>
        </ul>
    </div>
</nav>
</template>

<script>
export default {
    data() {
        return {
            show_menu: false
        }
    },
}
</script>

<style scoped>
a:not(.btn) {
    padding: 10px;
}

.collapse:not(.show) {
    display: block !important;
}

@media (min-width: 767.98px) {
  .navbar-nav {
    display: inline-flex !important;
  }
}


@media (max-width: 767.98px) {
    .navbar .navbar-collapse .navbar-nav {
        background-color: #191919;
        padding: 8px 20px;
        position: relative;
        top: 8px;
        width: 200px;
        z-index: 2;
    }

    .navbar .navbar-collapse li {
        border-bottom: #fff;
        padding: 10px;
    }

    /* a[data-v-f84c2348]:not(.btn):after {
    content: "";
    height: 2px;
    background: #ebebeb;
    position: absolute;
    bottom: -8px;
    left: 0;
    right: 0;
} */

    a[data-v-f84c2348]:not(.btn) {
        color: rgba(255, 255, 255, .7);
        font-size: 14px;
        letter-spacing: .35px;
        padding: 7px 0;
        margin-right: 32px;
    }

    .home-area .home-name {
      font-size: 50px !important;
    }
}
</style>
