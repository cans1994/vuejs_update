<template>
<div id="main">
  <nav v-bind:class="active" v-on:click.prevent>
    <a href="#" class="accueil" v-on:click="Accueil('Accueil')">Accueil</a>
    <a href="#" class="apropos" v-on:click="Apropos('Apropos')">À propos</a>
    <a href="#" class="mentionslegales" v-on:click="MentionsLegales('MentionsLegales')">Mentions Légales</a>
  </nav>
  </div>
</template>

<style coped>
#nav {
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: white;
}
</style>