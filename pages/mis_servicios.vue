<template>
    <div class="mis_servicios">
        <que_hago />
        <iconos />

    </div>
</template>

<script>
import que_hago from "../components/que_hago";
import iconos from "../components/iconos";
    export default {
        name: 'mis_servicios',
        layout: 'enpi',
        components: {
            que_hago,
            iconos
        }
    }
</script>

<style scoped>

</style>