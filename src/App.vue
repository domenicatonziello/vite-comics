<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'Vite Comics',
  components: { AppHeader, AppMain, AppFooter }
}
</script>
<template>
  <!-- Header -->
  <app-header></app-header>
  <!-- Main -->
  <app-main></app-main>
  <!-- Footer -->
  <app-footer></app-footer>
</template>


<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generic */
body {
  font-family: "Open Sans", sans-serif;
}

a {
  text-decoration: none;
}

ul {
  list-style-type: none;
}

/* Utils */
.container {
  max-width: 1000px;
  margin: 0 auto;
}
</style>