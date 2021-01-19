<template>
  <div id="customers columns">
    <div class="column">
      <div class="container is-large">
        <article class="media">
          <h1 class="margen fuente">Nuestros Clientes</h1>
          <p class="margen fuente">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa,
            suscipit rerum iste vero enim voluptatem reprehenderit aperiam
            quaerat beatae accusantium, vel ex nesciunt numquam dicta molestias
            voluptatum optio! Accusamus, et?
          </p>
        </article>
      </div>
      <div class="container is-medium">
        <article class="margen media fuente">
          <h2>Web</h2>
          <h3>Martha Reina Retail</h3>
        </article>
      </div>
      <div class="container">
        <h2 class="margen fuente">Auditoria y Ascesoramiento</h2>
        <article class="margen media fuente">
          <div class="media-left">
            <figure class="image is-96x96">
              <!-- <div class="name_company"> -->
              <img
                src="https://pbs.twimg.com/profile_images/1184854516547629056/k_czwwJM.jpg"
                alt="Granja"
              />
              <!-- </div> -->
            </figure>
          </div>
          <div class="name_company media-comtent">
            <div class="content">
              <h3>Granja Canina Dejando Huella</h3>
            </div>
          </div>
        </article>
      </div>
      <div class="container">
        <h2 class="margen fuente">Camáras</h2>
        <!-- aca inicia el articulo -->
        <article class="margen media fuente">
          <div class="media-left">
            <figure class="image is-96x96">
              <img
                src="http://animalsclub.co/petshop/image/catalog/petshoplogo-02.png"
                alt="animals"
              />
            </figure>
          </div>
          <div class="media-content">
            <div class="content">
              <h3>Animals Club</h3>
            </div>
          </div>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "customers"
};
</script>

<style scoped>
.name_company {
  display: inline-block;
  border: 2px solid black;
}
.row {
  text-align: left;
}
</style>
