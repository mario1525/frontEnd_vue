<template>
    <div class="menu">
        <div class="busq">
            <img src="../assets/busqueda.png" width="50px" height="50px">
        </div>
        <div >
            <button class="btn1 btnt"> Home</button>
        </div>
        <div >
            <button class="btn2 btnt">  tecnologias</button>
        </div>
        <div >
            <button class="btn3 btnt"> proyectos</button>
        </div>
        <div class="imgLogo">
            <img src="../assets/santaCruz.png" width="180px" height="180px">
        </div>
        <div >
            <button class="btn4 btnt"> modelos</button>
        </div>
        <div class="btn5 btnt">
            <button> repuestos</button>
        </div>
        <div>
            <button  class="btn6 btnt"> contacto</button>
        </div> 
        <div class="compra">
            <img src="../assets/carrito.png" width="50px" height="50px">
        </div>       
    </div>
</template>

<script>
export default {
    name: 'componet2Vue',
}
</script>

<style>

.menu{
    display: grid;
    height: 125px;
    grid-template-columns:1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr ;
    grid-template-rows: 124px;
    
}

table {
    text-align: center;
}

th {
    padding: 30px
}

button{
    background: transparent;
    border: transparent;
}
.btnt:hover {
    border-bottom: 4px solid #fb2e01;
}

;
</style>
