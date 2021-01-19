<template>
  <div clase="encabezado">
    <nav class="navbar-menu">
      <div class="navbar-brand">
        <nuxt-link to="/">
          <div class="logo">
            <img src="../assets/Logo.png" alt="Logo" />
          </div>
        </nuxt-link>
        <div class="navbar-end">
          <div class="enlaces navbar-item">
          <div class="fuente">
            <NuxtLink to="clientes">Clientes</NuxtLink>
            <NuxtLink to="informacion">Información</NuxtLink>
            <NuxtLink to="noticias">Noticias</NuxtLink>
            <NuxtLink to="servicios">Servicios</NuxtLink>
            <NuxtLink to="contacto">Contacto</NuxtLink>
          </div>
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
  justify-content: right;
}

.nuxt-link-active {
  color: azure;
}
a {
  text-decoration: none;
}
.navbar-menu {
  display: inline-flex;
  justify-content: baseline;
}
.navbar-brand {
  width: 67vw;
}
.navbar-end {
  background: yellowgreen;
  display: inline-block;
  justify-items: end;
  width: 33vw;
  margin-right: 0px;
  flex-grow: nowrap;
}
</style>
