<template>
  <div id="app">
    <AppHeader></AppHeader>
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import AppHeader from '@/components/AppHeader.vue';

export default {
  name: 'home',
  components: {
    AppHeader
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Muli&display=swap");

#app {
  font-family: "Muli", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  margin: 0 auto;
}
</style>
