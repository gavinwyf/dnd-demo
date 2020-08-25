<template>
  <div id="app">
    <Dnd/>
  </div>
</template>

<script>
import Dnd from "./components/dnd";

export default {
  name: "App",
  components: {
    Dnd
  }
};
</script>

<style>
#app {
  height: 100%;
  width: 100%;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
