<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <AnotherWorld />
</template>

<script>
import AnotherWorld from "./components/AnotherWorld.vue";
export default {
  name: "App",
  components: {
    AnotherWorld,
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
