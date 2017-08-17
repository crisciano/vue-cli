<template>
  <div id="app">
    <nav-cp></nav-cp>
    <container-cp></container-cp>
    <!-- <router-view></router-view> -->
    <footer-cp></footer-cp>
  </div>
</template>

<script>
import NavCp from '@/components/Nav'
import ContainerCp from '@/components/Container'
import FooterCp from '@/components/Footer'

export default {
  name: 'app',
  components: {
    NavCp,
    ContainerCp,
    FooterCp
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
