<template>
  <div class="encabezado">
    <div class="logo">
      <nuxt-link to="/">
        <img src="../assets/Logo.png" alt="Logo" />
      </nuxt-link>
    </div>
    <div class="enlaces fuente">
      <NuxtLink to="clientes" class="enlace enlace_u">Clientes</NuxtLink>
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
  right: 15%;
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
.enlace_u {
  margin-right: 3vw;
}
.nuxt-link-active {
  color: #f2f1e8;
}
a {
  text-decoration: none;
}

@media all and (max-width: 600px) {
  .encabezado {
    display: flex;
    height: 9vh;
    width: 99vw;
    flex-flow: column;
    justify-content: center;
    align-content: center;
  }

  .logo {
    display: flex;
    width: 100%;
    height: 50%;
    align-content: center;
    justify-content: center;
  }
  img {
    display: block;
    position: relative;
    width: 33vw;
    height: 6vh;
  }
  .enlaces {
    display: flex;
    flex-flow: row;
    height: 50%;
    width: 100%;
    align-content: center;
    justify-content: center;
  }
}
</style>
