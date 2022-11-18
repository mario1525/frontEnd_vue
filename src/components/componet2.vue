<template>
    <div class="menu">
        <div class="busq">
            <img src="../assets/busqueda.png" width="50px" height="50px">
        </div>
        <div class="btn1">
            <button> Home</button>
        </div>
        <div class="btn2">
            <button>  tecnologias</button>
        </div>
        <div class="btn3">
            <button> proyectos</button>
        </div>
        <div class="imgLogo">
            <img src="../assets/santaCruz.png" width="180px" height="180px">
        </div>
        <div class="btn4">
            <button> modelos</button>
        </div>
        <div class="btn5">
            <button> mantenimiento</button>
        </div>
        <div class="btn6">
            <button> contacto</button>
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
button:hover {
    border-bottom: 4px solid #fb2e01;
}

;
</style>
