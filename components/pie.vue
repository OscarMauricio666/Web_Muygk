<template>
  <div class="pie">
    <div class="container.is-fullhd">
      <div class="level">
        <div class="level-left">
          <div class="col_uno">aca van todos los atajos en lista</div>
        </div>
        <div class="level-right">
          <div class="col_dos">Redes Sociales</div>
        </div>
      </div>
    </div>
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
  position: relative;
  width: 50vw;
  margin-left: auto;
  margin-right: auto;
}
.col_dos {
  background-color: blue;
  display: inline-block;
  position: absolute;
  width: 50vw;
  margin-left: auto;
  margin-right: auto;
}
.pie {
  width: 100vw;
}
.columns {
  display: flex;
}
</style>
