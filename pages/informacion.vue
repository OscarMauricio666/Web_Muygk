<template>
  <div id="informacion">
    <encabezado />
    <h1>aqui se muestran los datos para contactar un formulario</h1>
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
export default {
  name: "informacion",
  components: {
    encabezado,
    pie
  }
};
</script>

<style scoped></style>
