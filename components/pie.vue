<template>
  <div class="pie fuente">
    <div class="container">
      <!-- ANCHOR Columna Uno -->
      <div class="col_uno">
        <div class="list">
          <div class="list-item">
            <h2>La Calera- Cundinamarca- Colombia</h2>
          </div>
          <div class="list-item">
            <h2>Soporte al Cliente</h2>
          </div>
          <div class="list-item">
            <h2>Nosotros</h2>
          </div>
        </div>
      </div>
      <!--ANCHOR Columna Dos -->
      <div class="col_dos">
        <div class="list">
          <div class="list-item">
            <h2>Clientes</h2>
          </div>
          <div class="list-item">
            <h2>Noticias</h2>
          </div>
          <div class="list-item">
            <h2>Información</h2>
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
  padding: 0.9%;
  box-sizing: border-box;
  position: relative;
  bottom: 0%;
  justify-content: center;
  background-color: #050533;
}
.container {
  margin: 0%;
  padding: 0%;
  display: flex;
  flex-direction: row;
  width: auto;
  flex-wrap: wrap;
  justify-content: space-around;
  color: #e34234;
}
.col_uno {
  display: flex;
  width: auto;
  padding: 0%;
  align-self: center;
  flex-direction: column;
}
.col_dos {
  display: flex;
  width: auto;
  padding: 0%;
  align-self: center;
  flex-direction: column;
}
.list {
  display: flex;
  flex-direction: column;
  margin: 0%;
  text-align: left;
}
.list-item {
  display: block;
  width: 100%;
  text-align: center;
  color: #e34234;
}
h2 {
  color: #e34234;
}
</style>
