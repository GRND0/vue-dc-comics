<template>
  <div id="app">
    <HeaderCustom />
    <MainCustom />
    <FooterCustom />
  </div>
</template>

<script>
import HeaderCustom from "./components/HeaderCustom.vue";
import FooterCustom from "./components/FooterCustom.vue";
import MainCustom from "./components/MainCustom.vue";

export default {
  name: "App",
  components: {
    HeaderCustom,
    FooterCustom,
    MainCustom,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
@import "./style/variables.scss";
</style>
