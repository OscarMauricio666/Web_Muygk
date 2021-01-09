<template>
  <div id="clientes">
    <encabezado />
    <h3 class="fuente">
      Estos bbbbbb son nuestrros clientes. Almost before we knew it, we had left
      the ground.
    </h3>
    <customers />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import customers from "../components/informacion/customers";
export default {
  name: "clientes",
  head: {
    title: "Nuestros Clientes"
  },
  components: {
    encabezado,
    pie,
    customers
  }
};
</script>

<style scoped></style>
