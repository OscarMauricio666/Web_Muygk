<template>
  <div class="noticias">s
    <news />
  </div>
</template>

<script>
import news from "../components/news";
export default {
  head: {
    title: "Noticias"
  },
  name: "noticias",
  components: {
    news
  },
  layout: 'en_pi'
};
</script>

<style scoped></style>
