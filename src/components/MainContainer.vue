<template>
  <div class="main-container">
    <!-- header -->
    <the-header></the-header>
    <!-- Google Title -->
    <google-title></google-title>
    <!-- input -->
    <main-input></main-input>
    <!-- google lang + flex-grow -->
    <google-lang></google-lang>
    <!-- footer -->
    <the-footer></the-footer>
  </div>
</template>

<script>
import GoogleLang from "./GoogleLang.vue";
import GoogleTitle from "./GoogleTitle.vue";
import MainInput from "./MainInput.vue";
import TheFooter from "./TheFooter.vue";
import TheHeader from "./TheHeader.vue";
export default {
  components: { TheHeader, GoogleTitle, MainInput, GoogleLang, TheFooter },
};
</script>

<style scoped>
.main-container {
  display: flex;
  flex-direction: column;
  height: 100%;
  flex-shrink: 0;
}
</style>
