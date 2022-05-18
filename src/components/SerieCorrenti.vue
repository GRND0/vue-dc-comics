<template>
  <div class="product">
    <img :src="DatiSerie.thumb" alt="" />
    <h4>{{ DatiSerie.series }}</h4>
  </div>
</template>

<script>
export default {
  name: "SerieCorrenti",
  props: {
    DatiSerie: Object,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
@import "../style/common.scss";
</style>
