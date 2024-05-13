<template>
  <div class="container-fluid">

    <section class="row">
      <Title />
    </section>
    <section class="row">
      <Portfolio />
    </section>
    <section class="row">
      <Footer />
    </section>

  </div>
</template>

<script>
import Portfolio from '../components/Portfolio.vue';
import Title from '../components/Title.vue'; import AboutMe from '../components/AboutMe.vue';
import Footer from '../components/Footer.vue'


export default {
  setup() {
    return {};
  },
  components: { Portfolio, Title, AboutMe, Footer }
}
</script>

<style scoped lang="scss"></style>
