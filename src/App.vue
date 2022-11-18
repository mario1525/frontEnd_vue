<template>
<div class="contenedor">  
  <componet2Vue/>  
  <HelloWorld msg="hello world vue"/> 
  <bodyVue/>
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
  background-image: none;
 
}
.contenedor{
  display: grid;
  height: 2500px;
  grid-template-columns: 1fr;
    grid-template-rows: auto auto auto;
}
</style>
