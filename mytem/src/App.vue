<template>
  <div>
        <header class="site-header">
    <div class="site-header__container container">
      <!-- SITENAV -->
      <nav class="sitenav">
        <a class="sitenav__logo" @click="home"><img class="logo-img" src="@/img/logo.svg" alt="mytem-logo"></a>
        <ul class="sitenav-list">
          <li class="sitenav__item"><router-link class="sitenav__link" to="/">Home</router-link></li>
          <li class="sitenav__item"><router-link class="sitenav__link" to="/about">About</router-link></li>
        </ul>
      </nav>
      <button @click="contact" class="site-header__nav--toggler button" type="button">contact us</button>
    </div>
  </header>
 <RouterView/>
  </div>

</template>

<script>
import { RouterLink, RouterView } from 'vue-router';

export default{
  data() {
    return {

    }
  },
  components: {


  },
  methods: {
    home(){
      this.$router.push({ name: "home" });
    },
    contact(){
      this.$router.push({ name: "contact" });
    },
  },
}
</script>



<style scoped>

</style>
