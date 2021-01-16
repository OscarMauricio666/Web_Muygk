<template>
  <div id="encabezado">
    <nav class="navbar">
      <div class="navbar-brand">
        <nuxt-link to="/">
          <div class="logo">
            <img src="../assets/Logo.png" alt="Logo" />
          </div>
        </nuxt-link>
        <div class="enlaces">
          <div class="fuente">
            <NuxtLink to="clientes">Clientes</NuxtLink>
            <NuxtLink to="informacion">Información</NuxtLink>
            <NuxtLink to="noticias">Noticias</NuxtLink>
            <NuxtLink to="servicios">Servicios</NuxtLink>
            <NuxtLink to="contacto">Contacto</NuxtLink>
          </div>
        </div>
      </div>
    </nav>
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
  align-content: flex-end;
}

.nuxt-link-active {
  color: azure;
}
a {
  text-decoration: none;
}
.logo {
  background: yellow;
}
</style>
