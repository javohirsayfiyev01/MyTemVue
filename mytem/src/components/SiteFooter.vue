<template>
  <section class="footer">
    <div class="footer__content container">
      <div class="footer__infoblock">
        <nav class="footer__sitenav sitenav">
        <a class="logo" @click="home"><img class="logo-img" src="@/img/logo.svg" alt="mytem-logo" width="160px" height="40px"></a>
        <ul class="footer__sitenav-list sitenav-list">
          <li class="sitenav__item"><RouterLink class="sitenav__link" to="/">Home</RouterLink></li>
          <li class="sitenav__item"><RouterLink class="sitenav__link" to="/about">About</RouterLink></li>
        </ul>
      </nav>
      <div class="footer__links">
        <p class="footer__links-label">
          987  Hillcrest Lane <br> Irvine, CA <br> California 92714 <br> Call Us : 949-833-7432
        </p>
      </div>
      <div class="footer__infoblock-socials">
        <div class="footer__infoblock-social">
          <a href="#" class="footer__infoblock-icon">
          <img src="@/img/icon-facebook.svg" alt="Facebook icon">
        </a>
        <a href="#" class="footer__infoblock-icon">
          <img src="@/img/icon-pinterest.svg" alt="Pinterest icon">
        </a>
        <a href="#" class="footer__infoblock-icon">
          <img src="@/img/icon-twitter.svg" alt="Twitter icon">
        </a>
        </div>
        <p class="footer_socials-desc">Copyright 2020. All Rights Reserved</p>
      </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {

    }
  },
  methods: {
    home(){
      this.$router.push({ name: "home" });
    },
  },

}
</script>
<style>

</style>