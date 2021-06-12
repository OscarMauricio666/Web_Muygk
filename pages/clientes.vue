<template>
  <div class="clientes">
    <customers />
  </div>
</template>

<script>
<<<<<<< HEAD
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import customers from "../components/informacion/customers";
export default {
  name: "clientes",
  head: {
    title: "Clientes"
=======
import customers from "../components/customers";
export default {
  name: "clientes",
  head: {
    title: "Nuestros Clientes",
>>>>>>> fonts_14_1_21
  },
  components: {
    customers,
  },
  layout: "en_pi",
};
</script>

<style scoped>
.clientes {
  padding: 3%;
}
</style>
