<template>
  <div id="news">
    <encabezado />
    <h2>Estas son las noticias mas destacadas por ahora</h2>
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
export default {
  name: "news",
  components: {
    encabezado,
    pie
  }
};
</script>

<style scoped></style>
