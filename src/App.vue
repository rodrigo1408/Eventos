<template>
  <div id="app">
    <MainHeader />
    <div class="container-fluid">
      <img src="./assets/logo.png">
      <router-view></router-view>
      <button type="button" name="button" class="btn btn-primary">Olá Mundo!</button>
    </div>
    <MainFooter />
  </div>
</template>

<script>
import MainHeader from "./components/layouts/header/Main";
import MainFooter from "./components/layouts/footer/Main";

export default {
  name: "App",
  components: {
    MainHeader,
    MainFooter
  }
};
</script>

<style src="./assets/sass/app.scss" lang="scss"></style>
