<template>
  <div class="contenitore-footer">
    <div class="nav-blu">
      <div class="wrapper-nav-blu">
        <ul>
          <li>
            <a href=""
              ><img
                src="../assets/img/buy-comics-digital-comics.png"
                alt=""
              />DIGITAL COMICS</a
            >
          </li>
          <li>
            <a href=""
              ><img src="../assets/img/buy-comics-merchandise.png" alt="" />DC
              MERCHANDISE</a
            >
          </li>
          <li>
            <a href=""
              ><img
                src="../assets/img/buy-comics-subscriptions.png"
                alt=""
              />SUBSCRIPTION</a
            >
          </li>
          <li>
            <a href=""
              ><img
                src="../assets/img/buy-comics-shop-locator.png"
                alt=""
              />COMIC SHOP LOCATOR</a
            >
          </li>
          <li>
            <a href=""
              ><img src="../assets/img/buy-dc-power-visa.svg" alt="" />DC POWER
              VISA</a
            >
          </li>
        </ul>
      </div>
    </div>
    <div class="footer-superiore">
      <div class="wrapper-superiore">
        <ul class="nav-footer">
          <h3>DC COMICS</h3>
          <li>
            <a href=""> </a>
          </li>
        </ul>
        <img
          class="logo-sottostante"
          src="../assets/img/dc-logo-bg.png"
          alt=""
        />
      </div>
    </div>
    <div class="footer-inferiore">
      <div class="wrapper-inferiore">
        <button>SIGN-UP NOW!</button>
        <div class="contenitore-social">
          <h3>FOLLOW US</h3>
          <img src="../assets/img/footer-facebook.png" alt="" />
          <img src="../assets/img/footer-twitter.png" alt="" />
          <img src="../assets/img/footer-youtube.png" alt="" />
          <img src="../assets/img/footer-pinterest.png" alt="" />
          <img src="../assets/img/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterCustom",
};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
@import "../style/common.scss";

.contenitore-footer {
  width: 100%;

  & .logo-sottostante {
    z-index: -1;
  }
  & .nav-blu {
    width: 100%;
    height: 120px;
    background-color: $colore-primario;
    display: flex;
    align-items: center;
    justify-content: center;

    & .wrapper-nav-blu {
      width: 80%;
      height: 80%;
    }

    & ul {
      display: flex;
      justify-content: space-between;
      height: 70%;
      list-style: none;
    }

    & img {
      height: 100%;
    }

    & a {
      text-decoration: none;
    }
  }

  & .footer-inferiore {
    height: 100px;
    width: 100%;
    background-color: $grigio-scuro;

    & .wrapper-inferiore {
      width: 80%;
      height: 100%;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    & .contenitore-social {
      width: 40%;
      display: flex;
      justify-content: space-evenly;
      align-items: center;

      & img {
        color: $grigio-chiaro;
      }

      & h3 {
        color: $colore-primario;
      }
    }
  }

  & .footer-superiore {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 400px;

    & .wrapper-superiore {
      width: 80%;
      display: flex;
    }
  }
}
</style>
