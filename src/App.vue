<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <hello></hello>
  <fantasy :user="user"></fantasy>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import hello from "./components/hello.vue";
import fantasy from "./components/fantasy.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    hello,
    fantasy,
  },
  data() {
    return {
      user: "poteto",
      age: 23,
      job: "white mage",
      level: 80,
    };
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
