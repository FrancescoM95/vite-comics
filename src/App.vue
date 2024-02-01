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

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Open Sans', sans-serif;
  min-height: 100vh;
}

img {
  display: block;
}

.container {
  max-width: 1180px;
  margin: 0 auto;
}
</style>