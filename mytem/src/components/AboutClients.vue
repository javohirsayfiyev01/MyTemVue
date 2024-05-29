<template>
  <section class="clients">
    <img class="clients__bg" src="@/img/clients__circle-bg.svg" alt="404">

    <div class="container">
      <div class="clients__title-header">
        <h2 class="clients__title">Some of our clients</h2>
      </div>
    <div class="clients__list">
      <a href="#" class="clients__item">
        <img class="clients__link" src="@/img/the-verge.svg" alt="The Verge" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="@/img/the-jakarta-post.svg" alt="Jakarta" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="@/img/the-guardian.svg" alt="The Guardian" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="@/img/techradar.svg" alt="Techradar" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="@/img/gadgets-now.svg" alt="Gadgets Now" >
      </a>
    </div>
    </div>
  </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.clients{
  position: relative;
  padding-top: 140px;
  padding-bottom: 140px;
  background-color: var(--state-green);
}
.clients__title-header{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 920px;
  height: 48px;
  margin: 0 auto 0;
  padding: 0;
}
.clients__title{
  margin: 0;
  padding: 0;
  text-align: center;
  font-weight: 700;
  font-size: 48px;
  line-height: 48px;
  color: var(--white);
}
.clients__list{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 45px;
  margin: 64px auto 0;
  padding: 0;
}
.clients__item:not(:last-child){
  margin-right: 79px;
}
.clients__bg{
  position: absolute;
  margin: 0;
  padding: 0;
  top: 0;
  left: 0;
}
</style>