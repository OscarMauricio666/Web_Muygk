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
import ascesorias from "../components/servicios_componentes/ascesorias.vue";
import camaras from "../components/servicios_componentes/camaras.vue";
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import web from "../components/servicios_componentes/web.vue";
export default {
  components: {
    encabezado,
    web,
    Ascesorias,
    Camaras,
    pie
  },
  name: "servicios"
};
</script>

<style scoped></style>
