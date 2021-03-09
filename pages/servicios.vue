<template>
  <div class="servicios">
    <web />
    <ascesorias />
    <marketing />
    <camaras />
  </div>
</template>

<script>
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
