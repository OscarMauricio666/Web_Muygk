<template>
  <div class="formu">
    <form action="shoreseis@gmail.com">
      <div>
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
      </div>
      <div class="field">
        <label class="label fuente">Asunto</label>
        <div>
          <input type="text" placeholder="Escribe el asunto aquí" />
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
            class="input is-danger"
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
        <p class="help is-danger">This email is invalid</p>
      </div>
      <div class="field fuente">
        <div class="control">
          <label class="checkbox">
            <input type="checkbox" />
            I agree to the <a href="#">terminos y condiciones</a>
          </label>
        </div>
      </div>
      <div class="field is-grouped">
        <div class="control">
          <button class="button is-link">Enviar</button>
        </div>
        <div class="control">
          <button class="button is-link is-light">Cancelar</button>
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
  margin: 3vw;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  flex-direction: column;
  padding: 2vw;
  border-radius: 3vh;
}
.field {
  display: block;
}
.bloque {
  display: block;
  width: 100%;
}
.row {
  display: flex;
}
</style>
