<template>
  <div class="en_pi">
    <header>
      <encabezado />
    </header>
    <section>
      <nuxt />
    </section>
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
</style>
