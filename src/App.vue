<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  name: 'Vite DC Comics',
  components: { AppHeader, AppMain, AppFooter }
};
</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
</template>

<style>
body {
  font-family: 'Open Sans', sans-serif;
}

img {
  display: block;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
}
</style>