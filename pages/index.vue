<template>
  <div id="app">
<<<<<<< HEAD
    <encabezado />
    <h2>uste sumerce</h2>
    <v-btn depressed color="error">
      Error
    </v-btn>
    <v-btn block><div class="fuente">Buena chino</div></v-btn>
    <v-btn class="mx-2" fab dark large color="purple">
      <v-icon dark>
        mdi-android
      </v-icon>
    </v-btn>
    <p class="fuentee">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex a magnam
      incidunt aliquam magni perferendis ratione sit provident quam laborum,
      sapiente dicta illum ducimus rem vel, libero dolores, in animi!
    </p>
=======
>>>>>>> fonts_14_1_21
    <main_body />
  </div>
</template>

<script>
<<<<<<< HEAD
import encabezado from "../components/desing/encabezado";
import main_body from "../components/main_body";
import pie from "../components/desing/pie";
export default {
  name: "app",
  head: {
    title: "Inicio"
  },
  data() {
    return {
      colors: ["primary", "secondary", "yellow darken-2", "red", "orange"],
      model: 0
    };
=======
import encabezado from "../components/encabezado";
import main_body from "../components/main_body";
import pie from "../components/pie";
import en_pi from "../layouts/en_pi";
export default {
  name: "app",
  head: {
    title: "Home"
>>>>>>> fonts_14_1_21
  },
  components: {
    encabezado,
    main_body,
    pie
  },
  layout: "en_pi"
};
</script>

<<<<<<< HEAD
<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.fuente {
  font-family: "Kufman", "cursive";
}
</style>
=======
<style></style>
>>>>>>> fonts_14_1_21
