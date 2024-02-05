<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppBonus from './components/AppBonus.vue';
import comics from './data/comics'


export default {
  name: 'Vite DC Comics',
  components: { AppHeader, AppMain, AppFooter, AppBonus },
  data: () => ({
    comics
  })
};
console.log(comics);
</script>

<template>
  <AppHeader />
  <AppMain :comics="comics" />
  <AppBonus />
  <AppFooter />
</template>

<style lang="scss">
@use './assets/scss/style.scss'
</style>