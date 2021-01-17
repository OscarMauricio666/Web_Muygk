<template>
  <div class="contacto">
    <encabezado />
    <h1 class="fuente margen">Contactanos</h1>
    <formu />
    <contact />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import contact from "../components/contact";
import formu from "../components/formu";
export default {
  name: "contacto",
  components: {
    encabezado,
    pie,
    contact,
    formu
  }
};
</script>

<style scoped>
.contacto {
  align-content: center;
  align-items: center;
}
</style>
