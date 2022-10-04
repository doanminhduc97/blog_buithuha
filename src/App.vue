<template>
  <div id="app" class="grid">
    <the-header />
    <the-nav-bar />
    <router-view/>
  </div>
</template>

<script>
import TheHeader from './components/header/TheHeader.vue'
import TheNavBar from './components/navbar/TheNavBar.vue'
export default {
  name: 'App',
  components: {
    TheHeader,
    TheNavBar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css/family=Roboto:300,400,500,700&display=swap&subset=vietnamese');
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: #2c3e50; */
  /* margin-top: 60px; */
}
</style>
