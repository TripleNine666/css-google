<template>
  <main-container></main-container>
</template>

<script>
import MainContainer from "./components/MainContainer.vue";
export default {
  components: {
    MainContainer,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
  min-width: 400px;
}
body,
input,
button {
  color: white;
  font-family: arial, sans-serif;
  font-size: 14px;
}
body {
  background: #202124;
}
#app {
  height: 100%;
}
</style>
