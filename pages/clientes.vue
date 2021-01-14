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
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import customers from "../components/customers";
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
