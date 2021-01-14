<template>
  <div id="noticias">
    <encabezado />
    <h2>Estas son laaas noticias mas destacadas por ahora</h2>
    <div>Cindy</div>
    <news />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/desing/encabezado";
import pie from "../components/desing/pie";
import news from "../components/news/news";
export default {
  name: "noticias",
  head: {
    title: "Noticias"
  },
  components: {
    encabezado,
    pie,
    news
  }
};
</script>

<style scoped></style>
