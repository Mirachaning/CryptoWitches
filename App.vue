<template>
  <div id="app">
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view/>
</div>
</template>

<style>
#app {
  background-color: #17151D;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
/* 
nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
