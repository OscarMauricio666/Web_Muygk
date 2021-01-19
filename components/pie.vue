<template>
  <div class="pie">
    <div class="container.is-fullhd">
      <div class="level">
      <!-- ANCHOR Columna Uno -->
        <div class="level-left">
          <div class="col_uno">
            <div class="list">
            <ul>
              <div class="list-item">
                <li>
                  <h2>Instagram</h2>
                </li>
              </div>
              <div class="list-item">
                <li>
                  <h2>Facebook acá  van los atajos</h2>
                </li>
              </div>
              <div class="list-item">
                <li>
                  <h2>Facebookododododod acá  van los atajos</h2>
                </li>
              </div>
            </ul>
          </div>
          </div>
        </div>
        <!--ANCHOR Columna Dos -->
        <div class="level-right">
          <div class="col_dos">
            <div class="list">
            <ul>
              <div class="list-item">
                <li>
                  <h2>Instagram</h2>
                </li>
              </div>
              <div class="list-item">
                <li>
                  <h2>Facebook acá  van los atajos</h2>
                </li>
              </div>
              <div class="list-item">
                <li>
                  <h2>Facebookododododod acá  van los atajos</h2>
                </li>
              </div>
            </ul>
          </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "pie"
};
</script>

<style scoped>
.col_uno {
  background-color:rgb(81, 81, 223);
  display: inline-block;
  position: relative;
  width: 50vw;
  margin-left: auto;
  margin-right: auto;
}
.col_dos {
  background-color: rgb(81, 81, 223);
  display: inline-block;
  position: absolute;
  width: 50vw;
  margin-left: auto;
  margin-right: auto;
}
.pie {
  width: 100vw;
}
.columns {
  display: flex;
}
.list {
  padding: 2vw;
  margin-left: 3px;
}
.list-item {
  padding: 2px;
}
</style>
