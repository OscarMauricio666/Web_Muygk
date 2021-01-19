<template>
  <div class="noticias">
    <h2>Estas son laaas noticias mas destacadas por ahora</h2>
    <div>Cindy</div>
    <news />
  </div>
</template>

<script>
import news from "../components/news";
export default {
  name: "noticias",
  components: {
    news
  },
  layout: 'en_pi'
};
</script>

<style scoped></style>
