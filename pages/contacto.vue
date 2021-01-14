<template>
  <div id="contacto">
    <encabezado />
    <p>informacion de contaccto</p>
    <contact />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import contact from "../components/informacion/contact";
export default {
  name: "contacto",
  head: {
    title: "Contacto"
  },
  components: {
    encabezado,
    pie,
    contact
  }
};
</script>

<style scoped></style>
