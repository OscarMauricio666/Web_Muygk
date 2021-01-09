<template>
  <div id="encabezado">
    <img src="../assets/Logo.png" alt="Logo" />
    <NuxtLink to="clientes">Clientes</NuxtLink>
    <NuxtLink to="contacto">Contacto</NuxtLink>
    <NuxtLink to="informacion">Información</NuxtLink>
    <NuxtLink to="noticias">Noticias</NuxtLink>
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
  border-color: black;
  font-family: "Goldman", cursive;
  background-color: black;
  margin: 0%;
  padding: 0%;
}
</style>
