<template>
  <div class="web dark_blue">
    <div class="item">
      <article>
        <div class="fila">
          <div class="titulo_2">
            <h2 class="margen fuente">WEB</h2>
          </div>
        </div>
        <div class="fila">
          <div class="parrafo">
            <p class="margen fuente parrafo">
              Este tiempo nos a hecho cambiar rapidamente, afortunadamente
              tenemos a la tecnología, para ayudarnos aceptar los cambios.
              Generamos tu pagina web a la medida, usamos las ultimas
              tecnologias en el mercado Contactanos
            </p>
          </div>
        </div>
      </article>
    </div>
  </div>
</template>

<script>
export default {
  name: "web",
};
</script>

<style scoped>
.web {
  display: flex;
  flex-direction: column;
  box-shadow: 9%;
  width: 81%;
  align-items: center;
  justify-content: center;
  margin: 3vh;
  background-color: #f2f1e8;
}
.item {
  display: flex;
  align-content: center;
  justify-content: center;
}
</style>
