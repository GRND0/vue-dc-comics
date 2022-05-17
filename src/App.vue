<template>
  <div id="app">
    <HeaderCustom />
    <main>POSTOTIENI</main>
    <FooterCustom />
  </div>
</template>

<script>
import HeaderCustom from "./components/HeaderCustom.vue";
import FooterCustom from "./components/FooterCustom.vue";

export default {
  name: "App",
  components: {
    HeaderCustom,
    FooterCustom,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
@import "./style/variables.scss";
</style>
