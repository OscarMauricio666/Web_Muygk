<template>
  <div id="clientes">
    <encabezado />
    <h3>Estos son nuestros clientes</h3>
    <clientes />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
import clientes from "../components/clientes";
export default {
  name: "clientes",
  components: {
    encabezado,
    pie,
    clientes
  }
};
</script>

<style scoped></style>
