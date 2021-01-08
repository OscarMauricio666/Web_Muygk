<template>
  <div id="clientes">
    <encabezado />
    <h3>Estos son nuestros clientes</h3>
    <customers />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
import customers from "../components/customers";
export default {
  name: "clientes",
  components: {
    encabezado,
    pie,
    customers
  }
};
</script>

<style scoped></style>
