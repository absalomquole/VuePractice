<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    
    <NewComp />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import NewComp from "./components/NewComp";
export default {
  name: "App",
  components: {
    HelloWorld,
    NewComp
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
