<template>
  <div id="app">
    <Menu/>
    <button v-on:click="say('Accueil')">Accueil</button>
    <button v-on:click="say('Apropos')">À propos</button>
    <button v-on:click="say('MentionsLegales')">Mentions légales</button>

    <Accueil/>
    <Apropos/>
    <MentionsLegales/>

    
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Accueil from './components/Accueil.vue'
import Apropos from './components/Apropos.vue'
import MentionsLegales from './components/MentionsLegales.vue'


export default {
  name: 'App',
  components: {
    Menu,
    Accueil,
    Apropos,
    MentionsLegales,

  },
}
</script>

<style>
#app {
  font-family: 'Staatliches', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
