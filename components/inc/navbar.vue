<template name="component-name">
    <div>
    <nav class="navbar-expand-md navbar fixed-top" id="navbar"><a class="navbar-brand" data-scroll="" href="#home-area">
      <!-- Navbar Logo-->
      <img class="img-fluid" src="img/img-kitzu-logo.png" alt="Logo"></a>
    <span class="navbar-menu ml-auto" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" role="button"><span class="btn-line"></span></span>
    <div class="collapse navbar-collapse order-1 order-lg-0" id="navbarSupportedContent">
      <!-- Navbar menu-->
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><nuxt-link to="about">About</nuxt-link></li>
        <li class="nav-item"><nuxt-link to="resume">Resume</nuxt-link></li>
        <li class="nav-item"><nuxt-link to="portfolio">Portfolio</nuxt-link></li>
        <li class="nav-item"><nuxt-link to="blog">Blog</nuxt-link></li>
        <li class="nav-item"><nuxt-link to="contact">Contact</nuxt-link></li>
      </ul>
    </div>
  </nav>
    </div>
</template>
<script>
export default {
}
</script>
<style scoped>
a:not(.btn) {
    padding: 10px;
}
</style>
