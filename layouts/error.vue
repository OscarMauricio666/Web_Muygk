<template>
  <div class="error">
    <!-- <span class="icon has-text-danger is-large"> esto es un ejemplo de icons
      <font-awesome-icon :icon="['fas', 'ban']" />
    </span> -->
    <div class="tex">
      <h1>Estas perdido</h1>
<<<<<<< HEAD
      <h2>Regresa con nosotros da click en el siguiente enlace</h2>
      <nuxt-link to="/"><button>Volver</button></nuxt-link>
    </section>
=======
      <br />
      <h2>Regresa con nosotros, da clicK en el botón volver</h2>
      <br />
    </div>
    <div class="container">
      <div class="columns is-centered">
        <div class="column is-half">
          <nuxt-link to="/">
            <div class="buttons btn">
              <button class="button is-success">
                Volver
              </button>
            </div>
          </nuxt-link>
        </div>
      </div>
    </div>
>>>>>>> fonts_14_1_21
  </div>
</template>

<script>
export default {
  name: "error"
};
</script>

<style scoped>
.error {
  align-content: center;
  align-items: center;
  text-align: center;
  justify-content: center;
  margin-top: 33vh;
}
.btn {
  display: block;
}
.tex {
  display: block;
}
</style>
