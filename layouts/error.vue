<template>
  <div id="error">
    <section>
      <span class="icon-text has-text-danger">
        <span class="icon">
          <i class="fas fa-3x"></i>
        </span>
        <span>Danger</span>
      </span>
      <h1>Estas perdido</h1>
      <h2>Regresa con nosotros da clicl en el siguiente enlace</h2>
      <nuxt-link to="/"><button>Volver</button></nuxt-link>
    </section>
  </div>
</template>

<script>
export default {
  name: "error"
};
</script>

<style scoped></style>
