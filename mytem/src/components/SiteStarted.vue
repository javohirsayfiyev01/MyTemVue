<template>
  <section class="started">
    <img class="started__bg" src="@/img/started__bg.svg" alt="404">
    <div class="started-container container">
      <div class="started__description">
        <h1 class="started__title">Ready to get started?</h1>
        <button class="started__toggler button" @click="contact" type="button">contact us</button>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  methods: {
    contact(){
      this.$router.push({ name: "contact" })
    }
  },
}
</script>
<style scoped>
.started{
  position: relative;
  width: 100%;
  height: 200px;
  padding-top: 76px;
  background-color: var(--light-coral);
}
.started__description{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 917px;
  height: 48px;
  margin: 0;
  padding: 0;
  margin-left: auto;
  margin-right: auto;
}
.started__title{
  font-weight: 700;
  font-size: 48px;
  line-height: normal;
  align-items: center;
  margin: 0;
  padding: 0;
  color: var(--state-green);
}
.started__toggler{
  background-color: var(--light-coral);
  color: var(--state-green);
}
.started__toggler:active{
  background-color: var(--state-green);
  color: var(--white);

}
.started__bg{
  position: absolute;
  margin: 0;
  padding: 0;
  bottom: 0;
  left: 0;
}

</style>