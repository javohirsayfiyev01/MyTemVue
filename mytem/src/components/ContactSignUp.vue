<template>
  <section class="singup">
    <img class="contact__bg-1 contact__bg" src="@/img/directors__bg-2.svg" alt="404" >

    <div class="singup__container container">

      <div>
          <h1 class="singup__title">Contact</h1>
            <ul class=" singup__icon-list">
        <h2 class="singup__list-title">Ask us about</h2>
          <li class=" singup__item">
            <div class="singup__icon-wrapper">
              <img src="@/img/features__icon-3.svg" alt="singup__icon" class="singup__icon">
              <div class="singup__icon-bg"></div>
            </div>
            <div>
            <p class="singup__description">
              The quality of our talent network
            </p>
            </div>
          </li>
          <li class="singup__item">
            <div class="singup__icon-wrapper">
              <img src="@/img/features__icon-1.svg" alt="singup__icon" class="singup__icon">
              <div class="singup__icon-bg"></div>
            </div>
            <div>
            <p class="singup__description">
              Usage & implementation of our software
            </p>
            </div>
          </li>
          <li class="singup__item">
            <div class="singup__icon-wrapper">
              <img src="@/img/features__icon-2.svg" alt="singup__icon" class="singup__icon">
              <div class="singup__icon-bg"></div>
            </div>
            <div>
            <p class="singup__description">
              How we help drive innovation
            </p>
            </div>
          </li>
      </ul>
      </div>


      <div class="input-group">
        <input class="input-group__input" type="text" placeholder="Name">
        <input class="input-group__input" type="text" placeholder="EmailAddress">
        <input class="input-group__input" type="text" placeholder="Company Name">
        <input class="input-group__input" type="text" placeholder="Title">
        <input class="input-group__input input-group__input-mes" type="text" placeholder="Message">
        <button class="input-group__input-btn" type="button">submit</button>
      </div>
    </div>
    <img class="contact__bg-2 contact__bg" src="../img/contact-bg.svg" alt="404">
  </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.singup{
  position: relative;
  height: 550px;
}
.singup__container{
  display: flex;
  margin-top: 120px;
}
.singnup__list{
  width: 540px;
  height: 346px;
  margin: 0;
  padding: 0;
  margin-top: 198px;
  margin-bottom: 140px;
  margin-left: 125px;
}
.singup__item{
  display: flex;
 align-items: center;
 gap: 12px;
  padding: 0;
  margin: 0;
}
.singnup__item:not(:last-child){
  margin-bottom: 32px;
}
.singup__description{
  width: 100%;
  font-weight: 600;
  font-size: 15px;
  line-height: 25px;
  margin: 0;
  padding: 0;
}
.singup__icon-wrapper{
  position: relative;
  width: 56px;
  text-align: center;
}

.singnup__icon{
  position: relative;
  z-index: 10;
}
.singup__icon-bg{
  position: absolute;
  width: 56px;
  height: 56px;
  margin: 0;
  padding: 0;
  bottom: 0;
  left:   8px;
  z-index: -1;
  border-radius: 80%;
  background-color: var(--police-blue);
}

.singup__title{
  width: 350px;
  height: 100px;
  margin: 0 0 16px;
  padding: 0;
  font-weight: 700;
  font-size: 64px;
  line-height: 100px;
}
.singup__list-title{
  width: 540px;
  height: 48px;
  margin: 0;
  padding: 0;
  margin-bottom: 32px;
  font-weight: 700;
  font-size: 32px;
  line-height: 48px;
  color: var(--light-coral);
}
.singup__icon-list{
  width: 540px;
  height: 312px;
  margin: 0;
  padding: 0;
}
.singup__item{
  display: flex;
  align-items: center;
  width: 540px;
  margin: 0;
  padding: 0;
}
.singup__item:not(:last-child){
  margin-bottom: 8px;
}
.singup__description{
  font-weight: 700;
  font-size: 18px;
}


.input-group{
  width: 542px;
  height: 420px;
  margin: 0 0 0 30px;
  padding: 0;
}
.input-group__input{
  width: 540px;
  height: 42px;
  margin: 0 0 24px 0;
  padding: 0 81px 17px 14px;
  border: none;
  border-bottom: 1px solid #979797;
  background-color: transparent;
  font-weight: 600;
  font-size: 15px;
  opacity: 60%;
  line-height: 25px;
  letter-spacing: -0.12px;
  color: var(--white);
}
.input-group__input::placeholder{
  color: var(--white);
}
.input-group__input-mes{
  padding: 0 81px 59px 14px;
  height: 84px;
}
.input-group__input-btn{
  width: 123px;
  height: 48px;
  border: none;
  border-radius: 30px;
  padding: 9px 32px 11px 32px;
  font-weight: 600;
  font-size: 18px;
  cursor: pointer;
  color: var(--jungle-green);
  background-color: var(--white);
}
.contact__bg{
  position: absolute;
  margin: 0;
  padding: 0;
}
.contact__bg-1{
  top: 0;
  left: 0;
}
.contact__bg-2{
  bottom: 0;
  right: 0;
}
</style>