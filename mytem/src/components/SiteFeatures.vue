<template>
    <section class="features">
      <div class="features-container container">
        <div class="features__info">
          <hr>
          <h1 class="features__title">Build & manage distributed teams like no one else.</h1>
        </div>

        <ul class="features__list">
          <li class="features__item">
            <div class="features__icon-wrapper">
              <img src="@/img/features__icon-3.svg" alt="features__icon" class="features__icon">
              <div class="features__icon-bg"></div>
            </div>
            <div>
            <h1 class="feature__title">Experienced Individuals</h1>
            <p class="feature__description">Our network is made up of highly experienced professionals who are passionate about what they do.
            </p>
            </div>
          </li>
          <li class="features__item">
            <div class="features__icon-wrapper">
              <img src="@/img/features__icon-1.svg" alt="features__icon" class="features__icon">
              <div class="features__icon-bg"></div>
            </div>
            <div>
              <h1 class="feature__title">Easy to Implement</h1>
            <p class="feature__description">Our processes have been refined over years of implementation meaning our teams always deliver.</p>
            </div>
          </li>
          <li class="features__item">
            <div class="features__icon-wrapper">
              <img src="@/img/features__icon-2.svg" alt="features__icon" class="features__icon">
              <div class="features__icon-bg"></div>
            </div>
            <div>
              <h1 class="feature__title">Enhanced Productivity</h1>
            <p class="feature__description">Our customized platform with in-built analytics helps you manage your distributed teams.</p>
            </div>
          </li>
        </ul>
      </div>
      <img class="featurse-bg" src="@/img/featurse-bg.svg" alt="404">
    </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.features{
  position: relative;
  z-index: 1;
  width: 100%;
  background-color: var(--state-green);
}
.features-container{
  display: flex;
}
.features__info{
  width: 445px;
  height: 250px;
  margin: 0;
  padding: 0;
  margin-top: 140px;
}
.features__info hr{
  width: 50px;
  height: 4;
  margin: 0;
  padding: 0;
  top: 0;
  left: 0;
  background-color: var(--light-coral);
}
.features__title{
  font-weight: 700;
  font-size: 48px;
  line-height: normal;
  margin: 0;
  padding: 0;
  padding-top: 54px;
}

.features__list{
  width: 540px;
  height: 346px;
  margin: 0;
  padding: 0;
  margin-top: 198px;
  margin-bottom: 140px;
  margin-left: 125px;
}
.features__item{
  display: flex;
  width: 540px;
  height: 94px;
  padding: 0;
  margin: 0;
}
.features__item:not(:last-child){
  margin-bottom: 32px;
}
.feature__title{
  cursor: pointer;
  width: 100%;
  font-weight: 700;
  font-size: 18px;
  line-height: 28px;
  margin: 0;
  padding: 0;
  color: var(--light-coral);
}
.feature__description{
  width: 100%;
  font-weight: 600;
  font-size: 15px;
  line-height: 25px;
  margin: 0;
  padding: 0;
  padding-top: 16px;
}
.features__icon-wrapper{
  position: relative;
  width: 72px;
  height: 72px;
  margin: 0;
  padding: 0;
  margin-right: 23px;
}
.features__icon{
  position: relative;
  z-index: 1;
}
.features__icon-bg{
  position: absolute;
  width: 56px;
  height: 56px;
  margin: 0;
  padding: 0;
  bottom: 0;
  left:   8px;
  border-radius: 80%;
  background-color: var(--police-blue);
}
.featurse-bg{
  position: absolute;
  margin: 0;
  padding: 0;
  bottom: 0;
  right: 0px;
}


</style>