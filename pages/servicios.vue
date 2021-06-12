<template>
  <div class="servicios">
<<<<<<< HEAD
    <encabezado />
    <web />
    <ascesorias />
    <camaras />
    <pie />
=======
    <web />
    <ascesorias />
    <marketing />
    <camaras />
>>>>>>> fonts_14_1_21
  </div>
</template>

<script>
<<<<<<< HEAD
import ascesorias from "../components/servicios_componentes/ascesorias.vue";
import camaras from "../components/servicios_componentes/camaras.vue";
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import web from "../components/servicios_componentes/web.vue";
export default {
  name: "servicios",
  head: {
    title: "Servicios"
  },
  components: {
    encabezado,
    web,
    ascesorias,
    camaras,
    pie
  }
};
</script>

<style scoped></style>
=======
import ascesorias from "../components/ascesorias.vue";
import Camaras from "../components/camaras.vue";
import web from "../components/web";
import marketing from "../components/marketing";
import Marketing from "../components/marketing.vue";
export default {
  head: {
    title: "Servicios",
  },
  components: { ascesorias, Camaras, web, marketing, Marketing },
  name: "servicios",
  layout: "en_pi",
};
</script>

<style scoped>
.servicios {
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
}
</style>
>>>>>>> fonts_14_1_21
