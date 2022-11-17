<template> 
  <HelloWorld msg="hello world vue"/> 
  <componet2Vue/>  
  <bodyVue/>  
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
  text-align: center;
  color: #2c3e50;
}
</style>
