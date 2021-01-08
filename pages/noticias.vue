<template>
  <div id="noticias">
    <encabezado />
    <h2>Estas son laaas noticias mas destacadas por ahora</h2>
    h1
    <news />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
import news from "../components/news";
export default {
  name: "noticias",
  components: {
    encabezado,
    pie,
    news
  }
};
</script>

<style scoped></style>
