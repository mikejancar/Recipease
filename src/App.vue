<template>
  <v-app id="app">
    <NavBar />
    <v-container>
      <v-layout>
        <v-flex>
          <v-layout>
            <v-flex xs12>
              <router-view />
            </v-flex>
          </v-layout>
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue';

export default {
  name: 'Home',
  components: {
    NavBar
  },
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
