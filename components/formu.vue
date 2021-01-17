<template>
  <div class="formu">
    <form action="shoreseis@gmail.com">
      <div class="field">
        <label class="label">Nombre</label>
        <div class="control">
          <input
            class="input is-success"
            type="text"
            placeholder="Escribe tu nombre aquí"
          />
        </div>
      </div>
      <div class="field">
        <label class="label">Asunto</label>
        <div class="control">
          <input
            class="input is-success"
            type="text"
            placeholder="Escribe el asunto aquí"
          />
          <span class="icon is-small is-left">
            <i class="fas fa-user"></i>
          </span>
          <span class="icon is-small is-right">
            <i class="fas fa-check"></i>
          </span>
        </div>
      </div>
      <div class="field">
        <label class="label">Message</label>
        <div class="control">
          <textarea class="textarea" placeholder="Buen día ......"></textarea>
        </div>
      </div>
      <div class="field">
        <label class="label">Tus datos de contacto, porfavor.</label>
        <div class="control has-icons-left has-icons-right">
          <input
            class="input is-danger"
            type="email"
            placeholder="escribe aquí telefono o correo para contactarte"
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
      <div class="field">
        <div class="control">
          <label class="checkbox">
            <input type="checkbox" />
            I agree to the <a href="#">terms and conditions</a>
          </label>
        </div>
      </div>
      <div class="field is-grouped">
        <div class="control">
          <button class="button is-link">Submit</button>
        </div>
        <div class="control">
          <button class="button is-link is-light">Cancel</button>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "formu"
};
</script>

<style scoped>
.formu {
  display: block;
  width: 93vw;
  margin: 3vw;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  padding: 2vw;
  border-radius: 3vh;
}
</style>
