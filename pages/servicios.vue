<template>
  <div class="servicios">
    <encabezado />
    <web />
    <ascesorias />
    <camaras />
    <pie />
  </div>
</template>

<script>
import ascesorias from "../components/ascesorias.vue";
import Camaras from "../components/camaras.vue";
import encabezado from "../components/encabezado";
import pie from "../components/pie.vue";
import web from "../components/web";
export default {
  components: { ascesorias, Camaras, web, encabezado, pie },
  name: "servicios"
};
</script>

<style scoped></style>
