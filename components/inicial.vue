<template>
    <div class="inicial">
        <h2>Hola Soy</h2>
        <h3>Camilo</h3>
        <h3>Diseñador</h3>
        <h3>Grafico</h3>
        <button>en que te puedo ayudar</button>
    </div>
</template>

<script>
    export default {
        name:'inicial'
    }
</script>

<style scoped>
.inicial {
    display: flex;
    flex-flow: column;
    width: 100vw;
    height: 39vh;
    background: grey;
    padding: 3%;
}
button {
    width: 9%;
}

</style>