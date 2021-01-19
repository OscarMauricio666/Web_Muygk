<template>
  <div class="clientes">
    <customers />
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import customers from "../components/customers";
import en_pi from "../layouts/en_pi";
export default {
  name: "clientes",
  head: {
    title: "Nuestros Clientes"
  },
  components: {
    encabezado,
    pie,
    customers
  },
  layout: "en_pi"
};
</script>

<style scoped></style>
