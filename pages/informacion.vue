<template>
  <div id="informacion">
    <encabezado />
    <h1>aqui se muestrran los datos para contactar un formulario</h1>
    <nosotros />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
import nosotros from "../components/nosotros";
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
