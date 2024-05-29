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
<style scoped>
.footer{
  width: 100%;
  height: 196px;
  padding-top: 48px;
  padding-bottom: 48px;
  background-color: var(--dark-green);
}
.footer__content{
  width: 100%;
  height: 100px;

}
.footer__infoblock{
  display: flex;
  height: 100%;
  justify-content: space-between;
  margin: 0;
  padding: 0;
  margin-left: auto;
  margin-right: auto;
}
.footer__sitenav{
  display: block;
  width: 285px;
  height: 100%;
  margin: 0;
  padding: 0;
}
.footer__sitenav-list{
  display: flex;
  justify-content: space-between;
  margin: 0;
  padding: 0;
  margin-top: 25px;
}
.footer__links{
  width: 445px;
  height: 100%;
  margin: 0;
  padding: 0;
}
.footer__links-label{
  font-weight: 600;
  font-size: 15px;
  color: var(--white);
  opacity: 60%;
  margin: 0;
  padding: 0;
}

.footer__infoblock-socials{
  width: 371px;
  height: 100%;
  margin: 0;
  padding: 0;
}
.footer__infoblock-social{
  display: flex;
  justify-content: end;
  gap: 20px;
  margin: 0;
  padding: 0;
}
.footer__infoblock-icon{
  margin: 0;
  padding: 0;
  width: 24px;
  height: 24px;
  right: 0;
  top: 0;
}
.footer_socials-desc{
  width: 255px;
  height: 25px;
  font-weight: 600;
  font-size: 15px;
  margin: 0;
  padding: 0;
  margin-top: 55px;
  margin-left: auto;
}

</style>