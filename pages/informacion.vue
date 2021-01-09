<template>
  <div id="informacion">
    <encabezado />
    <contact />
    <h1>aqui se muestrran los datos para contactar un formulario</h1>
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import nosotros from "../components/informacion/nosotros";
export default {
  name: "informacion",
  components: {
    encabezado,
    pie,
    nosotros
  }
};
</script>

<style scoped></style>
