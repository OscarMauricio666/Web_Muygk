<template>
  <div id="app">
    <encabezado />
    <main_body />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/encabezado";
import main_body from "../components/main_body";
import pie from "../components/pie";
export default {
  name: "app",
  components: {
    encabezado,
    main_body,
    pie
  }
};
</script>

<style></style>
