<template>
  <div class="informacion">
    <nosotros />
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import nosotros from "../components/nosotros";

export default {
  head: {
    title: "Información"
  },
  name: "Informacion",
  components: {
    encabezado,
    pie,
    nosotros
  },
  layout: "en_pi"
};
</script>

<style scoped></style>
