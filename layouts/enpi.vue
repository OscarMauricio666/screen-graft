<template>
    <div class="enpi">
        <encabezado />
        <Nuxt />
        <pie />
    </div>
</template>

<script>
import encabezado from "../components/encabezado";
import pie from "../components/pie";
    export default {
        name: 'enpi',
        components: {
            encabezado,
            pie
        }
    }
</script>

<style scoped>

</style>