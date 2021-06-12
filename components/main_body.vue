<template>
  <div class="main_body tran">
    <div class="margen">
      <picture>
        <img src="../assets/CosmoNauta.jpg" alt="Fondo" />
      </picture>
      <p class="fuente">TECNOLOGÍA A TU ALCANCE</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "main_body",
  data() {
    return {
      msg: "",
    };
  },
};
</script>

<style scoped>
.main_body {
  display: flex;
  flex-direction: column;
  width: 99vw;
  padding-left: 1.5vw;
  padding-right: 1.5vw;
  position: relative;
}
picture {
  min-height: 87%;
}
img {
  border-radius: 1.5%;
}
p {
  position: absolute;
  left: 9%;
  top: 66%;
  font-size: 3em;
  font-weight: bold;
  color: #e34234;
}
@media all and (max-width: 600px) {
  .main_body {
    display: flex;
    flex-direction: column;
    width: 99vw;
    padding-left: 1.5vw;
    padding-right: 1.5vw;
    position: relative;
  }
  picture {
    min-height: 87%;
  }
  img {
    border-radius: 1.5%;
  }
  p {
    position: absolute;
    left: 9%;
    top: 33%;
    font-size: 3em;
    font-weight: bold;
    color: #e34234;
  }
}
/* @media all and (max-width: 320px) {
  p {
    position: absolute;
    left: 9%;
    top: 33%;
    font-size: 3em;
    font-weight: bold;
    color: #e34234;
  }
} */
</style>
