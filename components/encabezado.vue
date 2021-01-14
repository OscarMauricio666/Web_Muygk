<template>
  <div id="encabezado">
    <nuxt-link to="/">
      <img src="../assets/Logo.png" alt="Logo" />
    </nuxt-link>
    <div class="enlaces">
      <div class="fuente">
        <NuxtLink to="contacto">Contacto</NuxtLink>
        <NuxtLink to="clientes">Clientes</NuxtLink>
        <NuxtLink to="informacion">Información</NuxtLink>
        <NuxtLink to="noticias">Noticias</NuxtLink>
        <NuxtLink to="servicios">Servicios</NuxtLink>
      </div>
    </div>
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
  background-color: black;
  margin: 0%;
  padding: 0%;
}
.enlaces {
  float: right;
  margin-top: 3vh;
  color: beige;
}

.nuxt-link-active {
  color: azure;
}
a {
  text-decoration: none;
}
</style>
