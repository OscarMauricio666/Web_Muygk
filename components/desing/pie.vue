<template>
  <div id="pie">
    <template>
      <v-footer dark padless>
        <v-card class="flex" flat tile>
          <v-card-title class="teal">
            <strong class="subheading">MuyKg instantes</strong>
            <v-spacer></v-spacer>
            <v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
              <v-icon size="24px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </v-card-title>
          <div class="texto_pie">
            <v-card-text class="py-2 white--text">
              {{ new Date().getFullYear() }} — <strong>MuyGk</strong>
            </v-card-text>
          </div>
        </v-card>
      </v-footer>
    </template>
  </div>
</template>

<script>
export default {
  name: "pie",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"]
  })
};
</script>

<style scoped>
.texto_pie {
  align-content: center;
  text-align: center;
  align-items: center;
}
</style>
