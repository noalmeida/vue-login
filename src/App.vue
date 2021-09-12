<template>
  <div id="nav">
    <router-link to="/login">Entrar</router-link>
  </div>
  <router-view />
</template>

<style>
#app {
}

#nav {
  display: grid;
  justify-items: center;
  margin-top: 15px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
}
</style>
