<template>
  <div class="hello">
    <div class="bike">
      <img src="../assets/bici1.png" width="500" height="400">
    </div>               
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello{
  display: grid;
  grid-template-columns: 500px 350px 500px;
  grid-template-rows: 153px auto;
  background-image: url(../assets/montaña.png);
  background-position: 200px;
  background-repeat: no-repeat;
  opacity: 0.8888;
}
.bike{
  grid-row: 2/3;
  grid-column: 2/3;  
}



</style>
