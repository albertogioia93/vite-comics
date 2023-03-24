<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
// TUTTI I FOGLI DI STILE DI main.css SONO VISIBILI IN TUTTO IL PROGETTO (IN ALTERNATIVA, FARE COME RIGA 4 DI MAIN.JS)
@use './assets/styles/main.scss' as *;
</style>
