<template>
  <div id="app">
    <main_body />
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import main_body from "../components/main_body";
import pie from "../components/pie";
import en_pi from "../layouts/en_pi";
export default {
  name: "app",
  components: {
    encabezado,
    main_body,
    pie
  },
  layout: "en_pi"
};
</script>

<style></style>
