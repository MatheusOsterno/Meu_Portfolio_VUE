<template>
<v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background}">
<NavBarTopo />
<v-container fluid>
  <v-row>
    <v-col cols="6">
      <v-img src="Matheus.png" contain max-height="500"></v-img>
    </v-col>
    <v-col cols="6">
      <h5 class="red--text text-darken-4 top">Olá, me chamo Matheus Osterno</h5>
      <h1 class="white--text">Sou desenvolvedor Front-End</h1>
      <p class="grey--text">
        Nesse portfólio mostro alguns de meus projetos.
      </p>
      <v-btn tile color="#A71210" dark>Baixe meu curriculo</v-btn>
    </v-col>
  </v-row>
</v-container>

</v-app>
</template>

<script>

import NavBarTopo from '../components/NavBarTopo.vue'

  export default {
    components: {
    NavBarTopo
},
  }
</script>

<style scoped>
.top{
  margin-top: 180px;
}
</style>
