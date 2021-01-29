<template>
    <div class="sobremi">
        <yo />
        <quien-soy />
        <trayectoria />

    </div>
</template>

<script>
import yo from "../components/yo";
import quien_soy from '../components/quien_soy.vue'
import trayectoria from '../components/trayectoria.vue'
    export default {
        name: 'sobremi',
        layout: 'enpi',
        components: {
            yo,
            quien_soy,
            trayectoria
        }
    }
</script>

<style scoped>

</style>