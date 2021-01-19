<template>
  <div class="en_pi">
    <encabezado />
    <nuxt />
    <pie />
  </div>
</template>

<script>
import pie from "../components/pie.vue";
import encabezado from "../components/encabezado";
export default {
  components: { pie, encabezado },
  name: "en_pi"
};
</script>

<style lang="css" scoped>

</style>
