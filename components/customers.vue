<template>
  <div class="customers">
    <div class="item">
      <article>
        <h1 class="margen fuente titulo_1">Nuestros Clientes</h1>
        <p class="margen fuente">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis
          nesciunt sapiente saepe eum. Sed corporis ratione quis! Fuga hic
          libero nam officiis quos architecto, unde, suscipit accusamus ratione
          quod earum.
        </p>
      </article>
    </div>
    <div class="item" v-for="servicio in servicios" :key="servicio.id">
      <article>
        <div class="fila">
          <div class="titulo_2">
            <h2 class="margen fuente">{{ servicio.nombre }}</h2>
          </div>
        </div>
        <div class="fila">
          <div class="titulo_3">
            <h3 class="margen fuente">{{ servicio.cliente }}</h3>
          </div>
          <div class="logo">
            <!-- Acá debe ir el logo -->
            <img src="" alt="" />
          </div>
        </div>
        <div class="fila">
          <div class="parrafo">
            <p class="margen fuente">
              {{ servicio.parrafo }}
            </p>
          </div>
        </div>
      </article>
    </div>
  </div>
</template>

<script>
export default {
  name: "customers",
  data() {
    return {
      servicios: [
        {
          id: "1",
          nombre: "Web",
          cliente: "Martha Reina Realtor",
          parrafo:
            "Martha Reina un gran persona que trabaja en Atlanta, Estados Unidos como agente de bienes raizes. Cuenta con una trayectoria de 15 años en el mercado",
        },
        {
          id: "2",
          nombre: "Auditoria y Ascesoramiento",
          cliente: "Granja Canina dejando Huella",
          parrafo:
            "Organización que presta servicios de cuidado de mascotas, con una trayectora de mas de 15 años en el mercado. se ha sabido matener como gran refernte en el sector de cuidado de mascotas en la ciudad de Bogotá",
        },
        {
          id: "3",
          nombre: "Camarás",
          cliente: "Animals Club",
          parrafo:
            "Organización dedicada al cuido de mascotas y su bienestar medico, gran atención en servicio de veterinaría ",
        },
      ],
    };
  },
};
</script>

<style scoped>
.logo {
  display: flex;
  width: 50%;
}
.parrafo {
  padding-left: 12%;
}

.margen {
  margin: 1.8%;
}
</style>
