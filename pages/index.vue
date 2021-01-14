<template>
  <div id="app">
    <encabezado />
    <h2>uste sumerce</h2>
    <main_body />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
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
