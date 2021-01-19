<template>
  <div class="contacto">
    <h1 class="fuente margen">Contactanos</h1>
    <formu />
    <contact />
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
  components: {
    encabezado,
    pie,
    contact,
    formu
  },
  layout: "en_pi"
};
</script>

<style scoped>
.contacto {
  align-content: center;
  align-items: center;
}
</style>
