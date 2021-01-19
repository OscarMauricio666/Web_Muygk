<template>
  <div class="servicios">
    <web />
    <ascesorias />
    <camaras />
  </div>
</template>

<script>
import ascesorias from "../components/ascesorias.vue";
import Camaras from "../components/camaras.vue";
import web from "../components/web";
export default {
  components: { ascesorias, Camaras, web },
  name: "servicios",
  layout: 'en_pi'
};
</script>

<style scoped></style>
