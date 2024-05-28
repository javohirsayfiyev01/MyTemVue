<template>
  <section class="clients">
    <div class="container">
      <div class="clients__title-header">
        <h2 class="clients__title">Some of our clients</h2>
      </div>
    <div class="clients__list">
      <a href="#" class="clients__item">
        <img class="clients__link" src="../img/the-verge.svg" alt="The Verge" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="../img/the-jakarta-post.svg" alt="Jakarta" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="../img/the-guardian.svg" alt="The Guardian" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="../img/techradar.svg" alt="Techradar" >
      </a>
      <a href="#" class="clients__item">
        <img class="clients__link" src="../img/gadgets-now.svg" alt="Gadgets Now" >
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
.clients__title-header{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 920px;
  height: 48px;
  margin: 140px auto 0;
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
</style>