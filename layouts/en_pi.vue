<template>
  <div class="en_pi">
    <header>
      <encabezado />
    </header>
    <article>
      <nuxt />
    </article>
    <footer>
      <pie />
    </footer>
  </div>
</template>

<script>
import pie from "../components/pie.vue";
import encabezado from "../components/encabezado";
export default {
  components: { pie, encabezado },
  name: "en_pi",
};
</script>

<style scoped>
header {
  margin: 0%;
}
article {
  background-color: #0d698b;
  margin-bottom: 0%;
  color: #f2f1e8;
}
footer {
  margin-top: 0%;
  color: #e34234;
}
</style>
