<template>
  <header>
    <img id="logo" src="../assets/logo.png" alt="Recipease logo" />
    <span>Recipease</span>
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
};
</script>

<style>
#logo {
  max-width: 75px;
  margin: 1.5em;
}

#nav {
  padding: 30px;
}

#nav a {
  text-decoration: none;
  font-size: 1.5em;
  font-weight: bold;
  color: whitesmoke;
  margin-right: 1.5em;
}

#nav a.router-link-exact-active {
  color: rgb(178, 255, 0);
}

header {
  background-color: green;
  display: flex;
  align-items: center;
}

header > span {
  color: whitesmoke;
  font-size: 2em;
  margin-right: 3em;
}
</style>
