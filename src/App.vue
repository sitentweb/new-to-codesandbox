<template>
  <div>
    <h1>New To CodeSandbox</h1>
    <p>Update this one also</p>
    <p>Directly updated from vscode</p>
    <NewComp />
  </div>
</template>

<script>
import NewComp from "./components/NewComp";
export default {
  name: "App",
  components: {
    NewComp,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
