<template>
  <img alt="Vue logo" src="./assets/tj.svg" />
  <ButtonCounter initialCount="2022" />
  <HelloWorld msg="This is my first Vue application" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import ButtonCounter from "./components/ButtonCounter.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    ButtonCounter,
  },
};
</script>

<style>
#app,
#app-extended {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
