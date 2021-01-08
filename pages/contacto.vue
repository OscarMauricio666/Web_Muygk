<template>
  <div id="contacto">
    <encabezado />
    <p>informacion de contaccto</p>
    <contact />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
import contact from "../components/contact";
export default {
  name: "contacto",
  components: {
    encabezado,
    pie,
    contact
  }
};
</script>

<style scoped></style>
