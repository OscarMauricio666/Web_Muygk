<template>
  <div class="encabezado">
    <div class="logo">
      <nuxt-link to="/">
        <img src="../assets/Logo.png" alt="Logo" />
      </nuxt-link>
    </div>
    <div class="enlaces fuente">
      <NuxtLink to="clientes" class="enlace">Clientes</NuxtLink>
      <NuxtLink to="informacion" class="enlace">Información</NuxtLink>
      <NuxtLink to="noticias" class="enlace">Noticias</NuxtLink>
      <NuxtLink to="servicios" class="enlace">Servicios</NuxtLink>
      <NuxtLink to="contacto" class="enlace">Contacto</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  name: "encabezado",
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<style scoped>
.encabezado {
  display: flex;
  height: 9vh;
  width: 99vw;
  flex-direction: row;
  flex-wrap: wrap;
  background-color: #050533;
}
.logo {
  width: 50%;
  margin: auto;
}

.enlaces {
  display: flex;
  flex-flow: row-reverse;
  right: 0%;
  height: 9vh;
  width: 50%;
}
.enlace {
  margin: auto;
  justify-content: center;
  margin-left: 1.5%;
  margin-right: 1.5%;
  font-weight: bold;
  color: #0d698b;
}
.nuxt-link-active {
  color: #f2f1e8;
}
a {
  text-decoration: none;
}
</style>
