<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppBonus from './components/AppBonus.vue';


export default {
  name: 'Vite DC Comics',
  components: { AppHeader, AppMain, AppFooter, AppBonus },
};
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppBonus />
  <AppFooter />
</template>

<style lang="scss">
@use './assets/scss/style.scss'
</style>