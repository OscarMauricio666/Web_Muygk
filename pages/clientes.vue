<template>
  <div class="clientes">
    <customers />
  </div>
</template>

<script>
import customers from "../components/customers";
export default {
  name: "clientes",
  head: {
    title: "Nuestros Clientes",
  },
  components: {
    customers,
  },
  layout: "en_pi",
};
</script>

<style scoped>
.clientes {
  padding: 3%;
}
</style>
