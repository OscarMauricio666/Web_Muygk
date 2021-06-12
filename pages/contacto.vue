<template>
  <div class="contacto">
    <div class="item">
      <formu />
      <contact />
    </div>
  </div>
</template>

<script>
<<<<<<< HEAD
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import contact from "../components/informacion/contact";
export default {
  name: "contacto",
  head: {
    title: "Contacto"
=======
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import contact from "../components/contact";
import formu from "../components/formu";
import en_pi from "../layouts/en_pi";
export default {
  name: "contacto",
  head: {
    title: "Contactanos",
>>>>>>> fonts_14_1_21
  },
  components: {
    encabezado,
    pie,
    contact,
    formu,
  },
  layout: "en_pi",
};
</script>

<style scoped>
.contacto {
  display: flex;
  flex-flow: column;
  align-content: center;
  align-items: center;
  margin-bottom: 0%;
}
.item {
  margin-top: 3vh;
}
</style>
