<template>
  <div id="informacion">
    <encabezado />
    <nosotros />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import nosotros from "../components/nosotros";
export default {
  name: "informacion",
  components: {
    encabezado,
    pie,
    nosotros
  }
};
</script>

<style scoped></style>
