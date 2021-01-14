<template>
  <div class="pie">
    <div class="col_uno">aca van todos los atajos en lista</div>
    <div class="col_dos">Redes Sociales</div>
  </div>
</template>

<script>
export default {
  name: "pie"
};
</script>

<style scoped>
.col_uno {
  background-color: red;
  display: inline-block;
  width: 50vw;
  position: relative;
}
.col_dos {
  background-color: blue;
  display: inline-block;
  width: 50vw;
  position: absolute;
}
.pie {
  width: 100vw;
}
</style>
