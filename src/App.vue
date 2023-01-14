<template>
  <TopNavbar></TopNavbar>
  <div class="top_nav_space"></div>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TopNavbar from './components/TopNavbar.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    TopNavbar,
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
body {
  box-sizing: content-box;
  margin: 0px;
}
.out1 {
  outline: 1px dashed green;
}
.top_nav_space {
  width: 100%;
  height: 50px;
  background-color: red;
}
</style>
