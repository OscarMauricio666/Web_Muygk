<template>
  <div id="contacto">
    <encabezado />
    <p>informacion de contacto</p>
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
export default {
  name: "contacto",
  components: {
    encabezado,
    pie
  }
};
</script>

<style scoped></style>
