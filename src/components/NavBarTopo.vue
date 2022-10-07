<template>
  <v-app-bar app color="#111111" dark flat class="px-8">
    <v-btn icon>
      <v-icon color="#a71210">fas fa-meteor</v-icon>
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll(home)">Home</v-btn>
    <v-btn text @click="scroll(projetos)">Projetos</v-btn>
    <v-btn text @click="scroll(sobre)">Sobre</v-btn>
    <v-btn text @click="scroll(Contato)">Contato</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({behavior: "smooth"});
    }
  }
}
</script>

<style>

</style>