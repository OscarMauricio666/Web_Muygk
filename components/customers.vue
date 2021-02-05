<template>
  <div class="container">
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
    <div class="item">
      <article>
        <div class="fila">
          <h2 class="margen fuente titulo_2">Web</h2>
        </div>
        <div class="fila">
          <div class="titulo_2">
            <h3 class="margen fuente">Martha Reina Retail</h3>
          </div>
          <div class="logo">
            <!-- Acá debe ir el logo -->
            <img src="" alt="" />
          </div>
        </div>
        <div class="fila">
          <div class="parrafo">
            <p class="margen fuente">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Repellendus, laboriosam dignissimos eligendi molestias molestiae
              veniam nostrum voluptatem facere quae, incidunt sapiente veritatis
              ipsa quia corrupti placeat labore modi, totam voluptatibus.
            </p>
          </div>
        </div>
      </article>
    </div>
    <div class="item">
      <article>
        <div class="fila">
          <h2 class="margen fuente titulo_2">Auditoria y Ascesoramiento</h2>
        </div>
        <div class="fila">
          <div class="titulo_2">
            <h3 class="margen fuente">Granja Canina Dejando Huella</h3>
          </div>
          <!-- <div class="logo">
            <img
              src="https://pbs.twimg.com/profile_images/1184854516547629056/k_czwwJM.jpg"
              alt="Granja"
            />
          </div> -->
        </div>
        <div class="fila">
          <div class="parrafo fuente margen">
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Harum
              iste eius unde error ducimus minima tempora qui. Accusantium,
              maxime, doloribus ullam quae nesciunt harum facere ea quod sequi
              neque deleniti?
            </p>
          </div>
        </div>
      </article>
    </div>
    <div class="item">
      <article>
        <h2 class="margen fuente">Camáras</h2>
        <!-- aca inicia el articulo -->
        <div class="fila">
          <div class="titulo_2">
            <h3 class="margen fuente">Animals Club</h3>
          </div>
          <!-- <div class="logo">
            <img
              src="http://animalsclub.co/petshop/image/catalog/petshoplogo-02.png"
              alt="animals"
            />
          </div> -->
        </div>
        <div class="fila">
          <div class="parrafo fuente margen">
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsa
              quia repudiandae cumque quod, fugit beatae vitae, delectus
              distinctio, odit deleniti amet vero fuga facere architecto totam
              ex. Minus, ex distinctio?
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
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
}
.item {
  display: flex;
  flex-direction: column;
  height: 20%;
}
.fila {
  display: flex;
  flex-direction: row;
  text-align: left;
  flex-basis: 0%;
}
.titulo_1 {
  display: flex;
  flex-direction: column;
  text-align: center;
  font-size: 6vh;
}
.titulo_2 {
  display: flex;
  flex-direction: column;
  width: 50%;
  text-align: left;
  justify-content: center;
  margin-left: 6%;
}
.logo {
  display: flex;
  width: 50%;
}
.parrafo {
  padding-left: 9%;
}

.margen {
  margin: 1.8%;
}
</style>
