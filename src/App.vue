<template>
  <div id="app">
    <v-blockly id="blockly"></v-blockly>
  </div>
</template>

<script>
import VBlockly from "v-blockly";
import "v-blockly/dist/VBlockly.css";

export default {
  name: "App",
  components: {
    "v-blockly": VBlockly,
  },
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
#blockly {
  height: 80vh;
}
</style>
