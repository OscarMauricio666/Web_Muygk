<template>
<<<<<<< HEAD
  <div id="informacion">
    <encabezado />
    <contact />
    <h1>aqui se muestrran los datos para contactar un formulario</h1>
    <pie />
=======
  <div class="informacion">
    <nosotros />
>>>>>>> fonts_14_1_21
  </div>
</template>

<script>
<<<<<<< HEAD
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import nosotros from "../components/informacion/nosotros";
export default {
  name: "informacion",
  head: {
    title: "Información"
  },
=======
import encabezado from "../components/encabezado";
import pie from "../components/pie";
import nosotros from "../components/nosotros";

export default {
  head: {
    title: "Información"
  },
  name: "Informacion",
>>>>>>> fonts_14_1_21
  components: {
    encabezado,
    pie,
    nosotros
  },
  layout: "en_pi"
};
</script>

<style scoped></style>
