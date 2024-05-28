<template>
  <div>
    <SiteHero/>
    <SiteFeatures/>
    <SiteDeliver/>
    <SiteStarted/>
    <SiteFooter/>
  </div>
</template>

<script>
import SiteHero from "../components/SiteHero.vue";
import SiteFeatures from "../components/SiteFeatures.vue";
import SiteDeliver from "../components/SiteDeliver.vue";
import SiteStarted from "../components/SiteStarted.vue";
import SiteFooter from "../components/SiteFooter.vue";

export default{
  data() {
    return {

    }
  },
  components:{
    SiteHero,
    SiteFeatures,
    SiteDeliver,
    SiteStarted,
    SiteFooter,
  }
}
</script>

<style>

</style>