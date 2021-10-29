<template>
    <div>
        <h1>  IL MIO PRIMO COMPONENTE  </h1>
        <br>
        <h3> {{m}} </h3>
        <button @click="m = 'Giallo'">Cambio colore</button>
    </div>
</template>
<script>

export default {
name : 'MioPrimoComponente',
data(){
    return{
        m: 'bianco'
    }
}
}

</script>
