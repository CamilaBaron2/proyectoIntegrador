<template>
  <div>
    <img class="imagen" alt="imagen" src="./assets/hands-2178566_1920.jpg">
    <img class="logo" src="./assets/logo-sanmateo.png" alt="logo">
    <Principal msg="Welcome to Your Vue.js App"/>
    <Definition msg="" />
    <FichaTecnica/>
  </div>
</template>

<script>
import Principal from './components/Principal'
import Definition from './components/Definition.vue'
import FichaTecnica from './components/fichaTecnica.vue';
export default {
  name: 'App',
  components: {
    Principal,
    Definition,
    FichaTecnica
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
