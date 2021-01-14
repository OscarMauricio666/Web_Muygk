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
import encabezado from "../components/encabezado";
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
