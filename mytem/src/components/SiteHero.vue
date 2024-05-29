<template>
    <section class="hero">
    <img class="hero-bg_1" src="@/img/header-bg_1.svg" alt="404">
    <div class="hero-container container">
      <div class="hero__content">
        <h1 class="hero__title">Find the <br> best <span>talent</span></h1>
        <div class="hero__text">
          <hr>
          <p>Finding the right people and building high performing teams can be hard. Most companies aren't tapping into the abundance of global talent. We're about to change that.</p>
        </div>
      </div>
    </div>
    <img class="hero-bg_2" src="@/img/header-bg_2.svg" alt="404">
  </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.hero{
  position: relative;
  margin-top: 250px;
  margin-bottom: 250px;
}
.hero-bg_1{
  position: absolute;
  margin: 0;
  padding: 0;
  margin-left: -100px;
}
.hero-bg_2{
  position: absolute;
  margin: 0;
  padding: 0;
  margin-top: 150px;
  padding-left: 60%;
}
.hero-container{
  width: 100%;
  height: 200px;
}
.hero__content{
  display: flex;
}
.hero__title{
  width: 635px;
  height: 200px;
  font-size: 100px;
  font-weight: 700;
  line-height: 100px;
  padding: 0;
  margin: 0;
  margin-right: 40px;
  color: var(--white);
}
.hero__title span{
  color: var(--light-coral);
}
.hero__text{
  width: 445px;
  height: 195px;
  margin: 0;
  padding: 0;
}
.hero__text p{
  font-size: 18px;
  line-height: 28px;
  padding-top: 83px;
  margin: 0;
}
.hero__text hr{
  width: 50px;
  height: 4px;
  margin: 0;
  padding: 0;
  top: 0;
  left: 0;
  background-color: var(--rapture-blue);
}


</style>