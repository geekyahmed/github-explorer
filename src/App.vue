<template>
  <div id="app">
    <Header/>
    <GithubExplorer/>
  </div>
</template>

<script>
import Header from "./components/Header";
import GithubExplorer from "./components/GithubExplorer";

export default {
  name: "App",
  components: {
    Header,
    GithubExplorer
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
