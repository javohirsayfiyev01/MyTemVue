<template>
  <section class="directors__section">
    <div class="directors__container container">
      <div class="directors__title-box">
          <h1 class="directors__title">Meet the directors</h1>
      </div>
      <div class="directors__list">
        <div class="director__item">
          <img class="director__img" src="../img/about__nikita.svg" alt="About Nikita">
          <div class="director__header">
            <h2 class="director__name">Nikita Marks</h2>
            <h3 class="director__name-job">Founder & CEO</h3>
          </div>
            <a class="director__item-icon" href="#" >
              <img class="director__icon-link" src="../img/about__+.svg" alt="404">
            </a>
          </div>
        <div class="director__item">
          <img class="director__img" src="../img/cristian.svg" alt="Cristian Duncan">
          <div class="director__header">
            <h2 class="director__name">Cristian Duncan</h2>
            <h3 class="director__name-job">Co-founder & COO</h3>
          </div>
            <a class="director__item-icon" href="#" >
              <img class="director__icon-link" src="../img/about__+.svg" alt="404">
            </a>
          </div>
        <div class="director__item">
          <img class="director__img" src="../img/cruz.svg" alt="Cruz Hamer">
          <div class="director__header">
            <h2 class="director__name">Cruz Hamer</h2>
            <h3 class="director__name-job">Co-founder & CTO</h3>
          </div>
            <a class="director__item-icon" href="#" >
              <img class="director__icon-link" src="../img/about__+.svg" alt="404">
            </a>
          </div>
        <div class="director__item">
          <img class="director__img" src="../img/drake.svg" alt="Drake Heaton">
          <div class="director__header">
            <h2 class="director__name">Drake Heaton</h2>
            <h3 class="director__name-job">Business Development Lead</h3>
          </div>
            <a class="director__item-icon" href="#" >
              <img class="director__icon-link" src="../img/about__+.svg" alt="404">
            </a>
          </div>
        <div class="director__item">
          <img class="director__img" src="../img/griffin.svg" alt="Griffin Wise">
          <div class="director__header">
            <h2 class="director__name">Griffin Wise</h2>
            <h3 class="director__name-job">Lead Marketing</h3>
          </div>
            <a class="director__item-icon" href="#" >
              <img class="director__icon-link" src="../img/about__+.svg" alt="404">
            </a>
          </div>

          <div class="director__item">
          <div class="director__header-allan">
            <h2 class="director__name director__name-allan">Aden Allan</h2>
            <h3 class="director__name-job director__job-description">
              “Empowered teams create truly amazing products. Set the north star and let them follow it.”
            </h3>
          <div class="director__icon">
            <a href="#" class="director__icon-allan">
              <img src="@/img/icon-facebook.svg" alt="Facebook icon" width="20" height="20">
            </a>
            <a href="#" class="director__icon-allan">
              <img src="@/img/icon-twitter.svg" alt="Twitter icon" width="20" height="20">
            </a>
          </div>
          </div>


            <a class="director__item-icon director__item-icon-allan" href="#" >
              <img class="director__icon-link" src="../img/about__+.svg" alt="404">
            </a>
          </div>
        </div>
    </div>
  </section>
</template>
<script>
export default {

}
</script>
<style>
.directors__section{
  width: 100%;
  height: 1002px;
  padding-top: 140px;
  margin-top: 140px;
  background-color: var(--jungle-green);
}
.directors__container{
  width: 100%;
  height: 722px;
}
.directors__title-box{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 920px;
  height: 48px;
  margin: 0 auto 64px;
  padding: 0;
}
.directors__title{
  margin: 0;
  padding: 0;
  text-align: center;
  font-weight: 700;
  font-size: 48px;
  line-height: 48px;
}
.directors__list{
  width: 100%;
  height: 610px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 76px 30px;
  margin: 0;
  padding: 0;
}
.director__item{
  width: 350px;
  height: 281px;
  padding: 0;
  margin: 0;
  text-decoration: none;
  background-color: var(--state-green);
}
.director__img{
  width: 96px;
  height: 96px;
  margin-left: 127px;
  margin-right: 127px;
  margin-top: 32px;
  margin-bottom: 16px;
}
.director__header{
  width: 302px;
  height: 73px;
  margin-left: 24px;
  margin-right: 24px;
}
.director__header-allan{
  height: 155px;
}
.director__name{
  margin: 0;
  padding: 0;
  text-align: center;
  font-weight: 700;
  font-size: 18px;
  line-height: 48px;
  cursor: pointer;
  color: var(--rapture-blue);
}
.director__name-allan{
  margin: 35px 24px 0;
}
.director__name-job{
  margin: 0;
  padding: 0;
  text-align: center;
  font-weight: 500;
  font-size: 15px;
  color: var(--white);
}
.director__job-description{
  font-weight: 600;
  margin: 8px 48px 0;
}
.director__item-icon{
  display: inline-block;
  width: 56px;
  height: 56px;
  padding: 20px;
  border-radius: 100%;
  margin-top: 25px;
  margin-right: 147px;
  margin-left: 147px;
  background-color: var(--light-coral);
}
.director__item-icon-allan{
  margin-top: 63px;
  background-color: var(--rapture-blue);
}
.director__icon-link{
  width: 16px;
  height: 16px;
  object-fit: contain;
}
.director__icon{
  display: flex;
  justify-content: space-between;
  width: 60px;
  height: 20px;
  margin: 24px 145px 0;
}
</style>