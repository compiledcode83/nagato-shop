<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  border: 1px solid black;
  background-color: black;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  color: white;
}

a {
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #d878f0;
}
</style>
