<template>
  <div id="app">
    <!-- <img width="25%" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Hello Vue in CodeSandbox!"/> -->
    <Navigation></Navigation>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld";
import Navigation from "./components/Navigation";

export default {
  name: "App",
  components: {
    Navigation
  }
};
</script>

<style>
/* #app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
