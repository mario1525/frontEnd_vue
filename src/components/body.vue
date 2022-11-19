<template>
    <div class="footer">
        <div class="descrip">
            <h3>EXPEDIA V2</h3>
            <p>La mejor bici para dh de santa cruz </p>
        </div>
        <div class="tipo">
            <img class="imgtip" src="../assets/mont.png" width="100px" height="100px">
            <h3>Downhill <br>
                  MTB</h3>
            
        </div>
        <div class="btns">
            <button class="btnCol">Get Color</button>
            <button class="btnde">Detalles</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'bodyVue'
}
</script>

<style>
.footer{
    display: grid;
    grid-template-columns: 220px 300px 110px 210px 300px;
    grid-template-rows: 200px;
}
.descrip{
    grid-column: 2/3;
}
.tipo{
    align-content: center;
    grid-column: 4/5;
    align-items: center;
}
.btns {
    grid-column: 5/6;
    display: grid;
    grid-template-columns: 120px 12px 120px;
    grid-template-rows: 24px;
}

.btnCol {
    grid-column: 1/2;
    gap: 10px;
    background-color: #fb2e01;
    color: aliceblue;
    width: 120px;
    height: 24px;
    border: transparent;
}

.btnde {
    grid-column: 3/4;
    background-clip: transparent;
    width: 120px;
    height: 24px;
    border: 1px solid black;
}


.btnde :hover {
    border-bottom: 0px solid black;
}
</style>