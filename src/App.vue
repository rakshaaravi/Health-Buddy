<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Snacks</router-link> |
      <router-link to="/about">Home</router-link> |
      <router-link to="/myprofile">Profile</router-link> |
      <router-link to="/meals">Meals</router-link> |
      <router-link to="/water">Water</router-link>
    </div>
    <router-view/>
  </div>
</template>



<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
