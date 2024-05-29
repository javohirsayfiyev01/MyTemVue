<template>
<section class="delivers">
  <img src="@/img/delivers-bg-left.svg" alt="404" class="delivers__img-bg__left delivers__img-bg">
  <div class="delivers-container container">
    <div class="delivers__title">
      <h1 class="deliver__title">
        Delivering real results for top companies. Some of our <span>success stories.</span>
      </h1>
    </div>
    <ul class="delivers__list">
      <div class="delivers__list-bg">
        <img class="delivers__item-bg" src="@/img/“.svg" alt="Delivers bg">
        <img class="delivers__item-bg" src="@/img/“.svg" alt="Delivers bg">
        <img class="delivers__item-bg" src="@/img/“.svg" alt="Delivers bg">
      </div>

      <li class="delivers__item">
        <p class="delivers__description">
          “The team perfectly fit the specialized skill set required. They focused on the most essential features helping us launch the platform eight months faster than planned.”
        </p>
        <div class="delivers__name">
          <h1 class="deliver__name">Kady Baker</h1>
          <h3 class="deliver__job-name">Product Manager at Bookmark</h3>
        </div>
        <div class="delivers__img">
          <img class="deliver__img" src="@/img/kady.svg" alt="Kady img">
        </div>
      </li>
      <li class="delivers__item">
        <p class="delivers__description">
          “We needed to automate our entire onboarding process. The team came in and built out the whole journey. Since going live, user retention has gone through the roof!”
        </p>
        <div class="delivers__name">
          <h1 class="deliver__name">Aiysha Reese</h1>
          <h3 class="deliver__job-name">Founder of Manage</h3>
        </div>
        <div class="delivers__img">
          <img class="deliver__img" src="@/img/aisha.svg" alt="Aisha img">
        </div>
      </li>
      <li class="delivers__item">
        <p class="delivers__description">
          “Amazing. Our team helped us build an app that delivered a new experience for hiring a physio. The launch was an instant success with 100k downloads in the first month.”
        </p>
        <div class="delivers__name">
          <h1 class="deliver__name">Arthur Clarke</h1>
          <h3 class="deliver__job-name">Co-founder of MyPhysio</h3>
        </div>
        <div class="delivers__img">
          <img class="deliver__img" src="@/img/arthur.svg" alt="Arthur img">
        </div>
      </li>
    </ul>
  </div>
  <img class="delivers__img-bg__right delivers__img-bg" src="@/img/delivers-bg-right.svg" alt="404">
</section>
</template>
<script>

export default {

}
</script>
<style scoped>
.delivers{
  padding-bottom: 140px;
}
.delivers__title{
  width: 932px;
  height: 96px;
  padding: 0;
  margin-top: 140px;
  margin-bottom: 56px;
  margin-left: auto;
  margin-right: auto;
  align-items: center;
}
.deliver__title{
  margin: 0;
  padding: 0;
  font-weight: 700;
  font-size: 48px;
  line-height: normal;
  text-align: center;
  justify-content: center;
}
.delivers__title span{
  color: var(--rapture-blue);
}
.delivers__list{
  position: relative;
  width: 100%;
  height: 313px;
  margin: 0;
  padding: 0;
}
.delivers__item{
  display: inline-block;
  position: relative;
  width: 350px;
  height: 266px;
  margin: 0;
  padding: 0;
  margin-top: 36px;
  margin-bottom: 11px;
  list-style: none;
  z-index: 10;
}
.delivers__item:not(:last-child){
  margin-right: 30px;
}
.delivers__list-bg{
  display: flex;
  position: absolute;
  margin: 0;
  padding: 0;
  margin-right: 142px;
  margin-left: 142px;
}
.delivers__item-bg:not(:last-child){
  margin: 0;
  padding: 0;
  margin-right: 312px;
}
.delivers__description{
  width: 100%;
  height: 100px;
  margin: 0;
  padding: 0;
  text-align: center;
  text-decoration: none;
}
.delivers__name{
  width: 100%;
  margin: 0;
  padding: 0;
  margin-top: 24px;
}
.deliver__name{
  margin: 0;
  font-weight: 700;
  font-size: 18px;
  text-align: center;
  color: var(--rapture-blue);
}
.deliver__job-name{
  font-weight: 500;
  font-size: 13px;
  text-align: center;
  margin: 0;
  margin-top: 2px;
}
.delivers__img{
  width: 100%;
  height: 62px;
  padding: 0;
  margin-top: 32px;
  margin-bottom: 11px;
}
.deliver__img{
  display: block;
  margin: 0;
  padding: 0;
  margin-left: auto;
  margin-right: auto;
}
.delivers{
  position: relative;
}
.delivers__img-bg{
  position: absolute;
  margin: 0;
  padding: 0;
}
.delivers__img-bg__left{
  top: -140px;
  left: 0;
}
.delivers__img-bg__right{
  bottom: -242px;
  right: 0;
}
</style>