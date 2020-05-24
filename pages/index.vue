<template>
<section class="home-area element-cover-bg" id="home" style="background-image:linear-gradient(rgba(0,0,0,.5), rgba(0,0,0,.5)),url(/images/jimgrad.jpg);background-position: inherit;background-blend-mode: luminosity;">
    <div class="container h-100">
      <div class="row h-100 align-items-center justify-content-center">
        <div class="col-12 col-lg-8 home-content text-center">
      <h1 class="home-name">James <span>Kiarie</span></h1>
        <h4>I’m a
        <vue-typer id="type-text"
          :text='["Web developer","Designer", "Freelancer", "Mobile developer"]'
          :repeat='Infinity'
          :shuffle='false'
          initial-action='typing'
          :pre-type-delay='200'
          :type-delay='100'
          :pre-erase-delay='2000'
          :erase-delay='250'
          erase-style='clear'
          :erase-on-complete='false'
          caret-animation='expand'
        >Hello john</vue-typer> 
        </h4>
        </div>
      </div>
    </div>
    <div class="fixed-wrapper">
      <!-- Languages list-->
      <div class="fixed-block block-left">
        <ul class="list-unstyled languages-list">
          <li><a href="#0"><span class="single-language">ENG</span></a></li>
        </ul>
      </div>
      <!-- Social media icons-->
      <div class="fixed-block block-right">
        <ul class="list-unstyled social-icons">
          <li><a href="#0"><i class="fab fa-twitter"></i></a></li>
          <li><a href="#0"><i class="fab fa-facebook"></i></a></li>
          <li><a href="#0"><i class="fab fa-linkedin"></i></a></li>
          <li><a href="#0"><i class="fab fa-github"></i></a></li>
          <li><a href="#0"><i class="fab fa-instagram"></i></a></li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  components: {
  },

}
</script>

<style>

span.vue-typer span.left[data-v-c41bac74], span.vue-typer span.right[data-v-c41bac74] {
    color: green;
  font-size: 30px;
}
.vue-typer {
  font-family: Copperplate, 'Copperplate Gothic Light', fantasy;
}

.vue-typer .custom.char.typed {
  color: #009e66;
}
.vue-typer .custom.char.selected {
  color: #009e66;
  background-color: transparent;
  text-decoration: line-through;
}
.vue-typer .custom.caret {
  background: #009e66;
  margin-left: 5px;
}

.home-area .home-name{
  font-size: 70px;
  color: #fff;
  letter-spacing: 1px;
  font-weight: 700;
}
</style>
