<template>
  <div class="nosotros">
    <div class="item dark_blue" v-for="info in nosotros" :key="info.id">
      <div class="fila">
        <div class="titulo_2">
          <h2 class="fuente margen">{{ info.nombre }}</h2>
        </div>
      </div>
      <div class="fila">
        <div class="parrafo">
          <p class="fuente margen">{{ info.parrafo }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "nosotros",
  data() {
    return {
      nosotros: [
        {
          id: 1,
          nombre: "Misíon",
          parrafo:
            "Contribuir a la sociedad al desarollo por el medio de la tecnología. Ser efectivo en el ambito tecnologico. Mantenemos investigación continua. Calidad en todos nuestros procesos",
        },
        {
          id: 2,
          nombre: "Visión",
          parrafo:
            "Contribución a nivel mundial en desarrollo de tecnología Software y Hardware. Proporcionando empleos en todo el mundo, Llevando al ser a aumentar su conciencia",
        },
      ],
    };
  },
};
</script>

<style scoped>
.nosotros {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.item {
  box-shadow: 9%;
  width: 81%;
  margin: 3vh;
  background-color: #f2f1e8;
}
</style>
