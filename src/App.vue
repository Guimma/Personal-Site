<template>
  <div id="app">
    <Sidenav msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Sidenav from './components/Sidenav.vue'

export default {
  name: 'App',
  components: {
    Sidenav
  }
}
</script>

<style>
#app {
  font-family: "Tommy", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
@font-face {
  font-family: "Tommy";
  src: local("Tommy"),
   url(./fonts/MADE_TOMMY_Regular.otf) format("truetype");
}
@font-face {
  font-family: "Tommy Bold";
  src: local("Tommy"),
   url(./fonts/MADE_TOMMY_Bold.otf) format("truetype");
}
@font-face {
  font-family: "Tommy Medium";
  src: local("Tommy"),
   url(./fonts/MADE_TOMMY_Medium.otf) format("truetype");
}
</style>
