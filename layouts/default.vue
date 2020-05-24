<template>
<div>
<myNavbar />
    <transition name="fade">
    <nuxt />
</transition>

 </div>

</template>

<script>
import myNavbar from '../components/inc/navbar'
export default {
components: {
  myNavbar,
},
  data () {
    return {}
  }
}
</script>

<style>


.fade-enter-active{
  transition: opacity 1s, transform 1s;
}
.fade-enter{
  opacity: 0;
  transform: rotateX(90deg);
}
</style>
