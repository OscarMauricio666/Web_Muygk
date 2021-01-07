<template>
  <div id="encabezado">
    <img src="../assets/Logo.png" alt="Logo" />
    <a href="prueba">PRUEBA</a>
    <!-- <router-link :to="{ name: 'servicios' }">Servicios</router-link>
    <router-link :to="{ name: 'nosotros' }">Nosotros</router-link>
    <router-link :to="{ name: 'clientes' }">Clientes</router-link>
    <router-link :to="{ name: 'noticias' }">Noticias</router-link> -->
  </div>
</template>

<script>
export default {
  name: "encabezado",
  data() {
    return {
      count: 0
    };
  }
};
</script>

<style scoped>
#encabezado {
  max-height: 10vh;
  background-color: white;
  border-color: black;
  font-family: "Goldman", cursive;
}
</style>
