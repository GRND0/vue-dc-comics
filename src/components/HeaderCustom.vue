<template>
  <div class="contenitore-header">
    <div class="contenitore-logo">
      <img class="logo" src="../assets/img/dc-logo.png" alt="" />
    </div>
    <div class="contenitore-nav">
      <ul class="nav">
        <li>
          <a href="">Prova Nav</a>
        </li>
        <li>
          <a href="">Prova Nav</a>
        </li>
        <li>
          <a href="">Prova Nav</a>
        </li>
        <li>
          <a href="">Prova Nav</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderCustom",
};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
@import "../style/common.scss";

.contenitore-header {
  width: 80%;
  height: 100px;
  background-color: white;
  display: flex;
  justify-content: space-around;
  align-items: center;

  & .contenitore-logo {
    height: 80%;
  }

  & .logo {
    height: 100%;
  }
}

.nav {
  display: flex;

  & li {
    margin: 0 1rem;
    list-style: none;
  }

  & a {
    text-decoration: none;
  }
}
</style>
