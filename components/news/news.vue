<template>
  <div class="news trans">
    <div class="titulo"><h2 class="fuente margen">titulo de Noticias</h2></div>
    <div class="parrafo">
      <p class="fuente margen">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque nemo
        qui, eius repellat eligendi commodi. Eaque non velit, repellat
        temporibus nesciunt rem expedita iste consectetur officiis ratione quod
        atque voluptatum.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "news",
};
</script>

<style scoped>
.news {
  display: flex;
  flex-direction: column;
  text-align: center;
  height: 66vh;
}
.titulo {
  width: 100%;
  height: 9%;
  display: block;
  position: relative;
  top: 0%;
}
.parrafo {
  margin: 3%;
  display: block;
}
</style>
