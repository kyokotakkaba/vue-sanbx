<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld msg="Hello Vue in CodeSandbox!"/>
    <Plugin/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Plugin from "./components/Plugin";

export default {
  name: "App",
  components: {
    HelloWorld,
    Plugin
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
