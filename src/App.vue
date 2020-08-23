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

<style lang="less">
@import "../node_modules/bootstrap/dist/css/bootstrap.min.css";
@import "../node_modules/@fortawesome/fontawesome
free/css/all.min.css";
#app {
  background: #eeeeee;
  min-height: 100vh;
}
</style>