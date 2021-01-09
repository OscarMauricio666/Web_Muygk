<template>
  <div id="clientes">
    <encabezado />
    <h3 class="fuente">
      Estos son nuestrros clientes Lorem ipsum dolor sit amet consectetur
      adipisicing elit. Aspernatur provident quidem, nemo earum ea voluptate
      placeat, cupiditate eveniet tempore beatae voluptates numquam consequuntur
      corporis esse facere magni facilis at nobis.
    </h3>
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
