<template>
  <div id="app">
    <!--<div id="nav">-->
    <!--<router-link to="/">Home</router-link> |-->
    <!--<router-link to="/about">About</router-link>-->
    <!--</div>-->
    <div class="overlay"></div>
    <router-view />
    <p class="contact">info@yedincibasamak.com</p>
  </div>
</template>

<style lang="scss">
html,
body,
#app {
  height: 100%;
  margin: 0;
  background-color: #65d381;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center;
  background-color: #65d381;
  position: relative;
}
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.contact {
  color: hsl(169, 37%, 11%);
  font-size: 35px;
  font-weight: 900;
  letter-spacing: -1.4px;
  margin: 0;
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
