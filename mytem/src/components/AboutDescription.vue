<template>
  <section class="about__description">
    <div class="about__description-box container">
      <h1 class="about__title">About</h1>
      <div class="about__paragraf-body">
        <p class="about__paragraf">
          We help companies build dynamic teams made up of top global talent. Using our network of passionate professionals we drive innovation and deliver incredible outcomes. Talented, diverse teams shape the best products and experiences. We'll bring those teams to you.
        </p>
      </div>
    </div>
    <img class="about__desc-bg" src="@/img/about__desc-bg.svg" alt="">
  </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.about__description{
  position: relative;
}
.about__description-box{
  display: flex;
  margin-top: 120px;
}
.about__title{
  width: 350px;
  margin: 0;
  padding: 0;
  margin-right: 30px;
  font-weight: 700;
  font-size: 64px;
  line-height: 100px;
}
.about__paragraf-body{
  width: 730px;
  height: 156px;
  bottom: 0;
  right: 0;
}
.about__paragraf{
  margin: 0;
  padding: 0;
  margin-top: 44px;
  font-weight: 600;
  font-size: 18px;
  line-height: 28px;
}
.about__desc-bg{
  position: absolute;
  margin: 0;
  padding: 0;
  bottom: 0;
  right: 0;
  top: 98px;
}
</style>