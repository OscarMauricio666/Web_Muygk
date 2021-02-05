<template>
  <div class="pie fuente">
    <div class="container">
      <!-- ANCHOR Columna Uno -->
      <div class="col_uno">
        <div class="list">
          <div class="list-item">
            <h2>Instagram</h2>
          </div>
          <div class="list-item">
            <h2>Facebook acá van los atajos</h2>
          </div>
          <div class="list-item">
            <h2>Facebookododododod acá van los atajos</h2>
          </div>
        </div>
      </div>
      <!--ANCHOR Columna Dos -->
      <div class="col_dos">
        <div class="list">
          <div class="list-item">
            <h2>Instagram</h2>
          </div>
          <div class="list-item">
            <h2>Facebook acá van los atajos</h2>
          </div>
          <div class="list-item">
            <h2>Facebookododododod acá van los atajos</h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "pie",
};
</script>

<style scoped>
.pie {
  display: flex;
  width: 100%;
  margin: 0%;
  padding: 0%;
  align-content: center;
  align-items: center;
  justify-content: center;
  box-sizing: border-box;
  position: relative;
  bottom: 0%;
}
.container {
  margin: 0%;
  padding: 0%;
  display: flex;
  flex-direction: row;
  width: 100%;
  align-items: center;
  align-content: center;
  flex-wrap: wrap;
  justify-content: center;
}
.col_uno {
  display: flex;
  width: auto;
  margin: auto;
  padding: 0%;
  align-self: center;
}
.col_dos {
  display: flex;
  width: auto;
  margin: auto;
  padding: 0%;
  align-self: center;
}
.list {
  display: flex;
  margin: auto;
  flex-direction: column;
  margin: 0%;
  padding: 3%;
  text-align: center;
}
</style>
