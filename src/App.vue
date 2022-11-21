<template>
  <div class="contenedor">
    <componet2Vue />       
    <HelloWorld />
    <bodyVue />     
  </div>
</template>

<script>
import bodyVue from './components/body.vue';
import componet2Vue from './components/componet2.vue';
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    componet2Vue,
    HelloWorld,
    bodyVue

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #fffeb3;


}

.contenedor {
  display: grid;
  height: 800px;
  grid-template-columns: 1fr;
  grid-template-rows: 124px 476px 200px;
}
</style>
