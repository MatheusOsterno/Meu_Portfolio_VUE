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
        Nesse portfólio mostro alguns de meus projetos e habilidades.
      </p>
      <v-btn tile color="#A71210" dark>Baixe meu curriculo</v-btn>
    </v-col>
    <v-col cols="12" class="padd">
      <div class="first" id="projeto">
        <v-row>
          <v-col cols="12">
            <!--Primeiro quadrado-->            
            <div class="child bgColor1">
              <v-icon color="#a71210" x-large class="ml-3">
                mdi-file-code
              </v-icon>
              <h3 class="white--text ml-3 mt-4">Desenvolvedor</h3>
              <p class="grey--text ml-3 mt-6">
                Sempre a procura de novas tecnologias.
              </p>
              <v-btn color="#A7121D" dark  text>
                Tecnologias
                <v-icon right>mdi-arrow-right</v-icon>
              </v-btn>
            </div>
            <!-- Segundo quadrado-->
            <div  class="child bgColor2">
              <v-icon x-large class="ml-3" dark>mdi-play</v-icon>
              <h3 class="white--text ml-3 mt-4">Youtuber</h3>
              <p class="grey--text ml-3 mt-6">
                Sempre a procura de novas tecnologias.
              </p>
              <v-btn  dark  text>
                Youtuber
                <v-icon right>mdi-arrow-right</v-icon>
              </v-btn>
            </div>
            <!--Terceiro quadrado-->
            <div class="child bgColor1">
              <v-icon color="#a71210" x-large class="ml-3">
                mdi-book-open-page-variant
              </v-icon>
              <h3 class="white--text ml-3 mt-4">Formação</h3>
              <p class="grey--text ml-3 mt-6">
                Sempre a procura de novas tecnologias.
              </p>
              <v-btn color="#A7121D" dark  text>
                Tecnologias
                <v-icon right>mdi-arrow-right</v-icon>
              </v-btn>
            </div>
          </v-col>
          <v-col cols="12" class="mt-10">
            <div class="child1">
              <h1 class="red--text-darken-4 mt-4 number">12</h1>
              <h3 class="white--text mt-4">Anos de experiencia</h3>
            </div>
            <div class="child2 mRight">
              <v-row>
                <v-col cols="12"></v-col>
              </v-row>
            </div>
          </v-col>
        </v-row>
      </div>
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
.topInverse{
  margin-top: -150px;
}
.topTolbar{
  margin-top: 100px;
  text-align: center;
}
.first{
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second{
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1{
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child{
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1{
  background-color: #1e1e1e;
}
.bgColor2{
  background-color: #ce1d2a;
}
.child1{
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2{
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight{
  margin-right: 8px;
}
.mButton{
  margin-bottom: 8px;
}
.padding{
  padding: 8px 0;
}
.col-12.padd{
  padding: 12px 0 !important;
}
.coll-12.childcol{
  padding: 0 !important;
}
h1.number{
  font-size: 50px;
  font-weight: bold;
}
</style>
