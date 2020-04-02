<template>
  <div id="app">
    <img alt="Vue logo" src="https://endureblaze.cn/images/avatar.png" />
    <HelloWorld msg="虽然我还不会前端但是先整上花里胡哨的东西" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
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
