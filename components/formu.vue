<template>
  <div class="formu">
    <form action="shoreseis@gmail.com" class="margen">
      <div>
        <div class="titulo_1 dark_blue">
          <h1>Contactanos</h1>
        </div>
        <div class="field">
          <label class="label fuente">Nombre</label>
          <div class="control">
            <input
              type="text"
              placeholder="Escribe tu nombre aquí"
              class="bloque"
            />
          </div>
        </div>
        <div class="field">
          <label class="label fuente">Asunto</label>
          <div>
            <input
              type="text"
              placeholder="Escribe el asunto aquí"
              class="bloque"
            />
          </div>
        </div>
        <div class="field">
          <label class="label fuente">Mensaje</label>
          <div class="control">
            <textarea class="textarea" placeholder="Buen día ......"></textarea>
          </div>
        </div>
        <div class="field">
          <label class="label fuente">Tus datos de contacto, porfavor.</label>
          <div class="control">
            <input
              class="input bloque"
              type="email"
              placeholder="Escribe aquí telefono o correo para contactarte"
            />
            <span class="icon is-small is-left">
              <i class="fas fa-envelope"></i>
            </span>
            <span class="icon is-small is-right">
              <i class="fas fa-exclamation-triangle"></i>
            </span>
          </div>
        </div>
        <div class="field fuente">
          <div class="control">
            <label class="checkbox">
              <input type="checkbox" />
              I agree to the <a href="#">terminos y condiciones</a>
            </label>
          </div>
        </div>
        <div class="field is-grouped botones">
          <div class="control enviar">
            <button class="button is-link is is-focus fuente is-rounded enviar">
              Enviar
            </button>
          </div>
          <div class="control cancelar">
            <button
              class="button is-link is-light fuente is-outlined is is-rounded is-danger"
            >
              Cancelar
            </button>
          </div>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "formu",
  transitions: "home",
};
</script>

<style scoped>
.formu {
  display: flex;
  width: 93vw;
  margin: auto;
  border-top: 3vh;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  flex-direction: column;
  border-radius: 3vh;
  background-color: #f2f1e8;
  border-top: 3vh;
}
.top {
  margin-top: 3vh;
}
.field {
  display: block;
}
.label {
  color: #050533;
}
.bloque {
  display: block;
  width: 100%;
}
.row {
  display: flex;
}
.botones {
  display: flex;
  flex-flow: row;
}
.enviar {
  width: 81%;
}
.cancelar {
  width: 15%;
  right: 0.3px;
}
@media all and (max-width: 600px) {
  .cancelar {
    position: relative;
    right: 9%;
  }
}
</style>
