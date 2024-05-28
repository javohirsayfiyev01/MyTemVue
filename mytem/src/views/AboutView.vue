<template>
  <div>
<AboutDescription/>
<AboutDirectors/>
<AboutClients/>
<SiteStarted/>
<SiteFooter/>
  </div>
</template>

<script>
import AboutDescription from "../components/AboutDescription.vue";
import AboutDirectors from "../components/AboutDirectors.vue";
import AboutClients from "../components/AboutClients.vue";
import SiteStarted from "../components/SiteStarted.vue";
import SiteFooter from "../components/SiteFooter.vue";
export default{
  data() {
    return {

    }
  },
  components: {
    AboutDescription,
    AboutDirectors,
    AboutClients,
    SiteStarted,
    SiteFooter,
  },
}
</script>



<style>

</style>
