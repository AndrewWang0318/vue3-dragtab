<template>
  <nav>
    <router-link to="/Home?id=1">Home</router-link> |
    <router-link to="/About?id=2">About</router-link> |
    <router-link to="/Error">Error</router-link> |
    <router-link to="/Title">Title</router-link>
  </nav>
  <router-view></router-view>
  <DragTab/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
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
