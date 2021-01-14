<template>
  <div id="contacto">
    <encabezado />
    <p>informacion de contaccto</p>
    <section>
      <h2>telefono: 319257100</h2>
      <h2>correo: servicios@muygk.com</h2>
    </section>
    <contact />
    <pie />
  </div>
</template>

<script>
import encabezado from "../components/Encabezado";
import pie from "../components/pie";
import contact from "../components/contact";
export default {
  name: "contacto",
  components: {
    encabezado,
    pie,
    contact
  }
};
</script>

<style scoped></style>
