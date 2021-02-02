<template>
  <div class="index">
    <inicial />
    <galeria />
    <servicios />
  </div>
</template>
<script>
import inicial from "../components/inicial.vue"
import galeria from "../components/galeria";
import servicios from "../components/servicios.vue"

  export default {
    name: 'index',
    layout: 'enpi',
    components: {
      inicial,
      galeria,
      servicios
    }
  }
</script>

<style scoped>


</style>