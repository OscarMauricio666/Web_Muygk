<template>
  <div class="contacto">
    <div class="item">
      <formu />
      <contact />
    </div>
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import contact from "../components/contact";
import formu from "../components/formu";
import en_pi from "../layouts/en_pi";
export default {
  name: "contacto",
  head: {
    title: "Contactanos",
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
