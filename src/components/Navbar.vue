<template>
  <nav class="container-fluid coll-12 font">
    <router-link class="" :to="{ name: 'HomePage' }">
      <img class="img-fluid logo" src="/src/assets/img/HJ.jpg" alt="HJ logo ">

    </router-link>
    <router-link :to="{ name: 'AboutPage' }">
      About Me
    </router-link>

  </nav>
</template>

<script>
import { RouterLink } from 'vue-router';
export default {
  setup() {

    return {

    }
  },

}
</script>

<style scoped>
.font {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
}

.logo {
  max-width: 20px;
  max-height: 20px;
}

@media screen and (min-width: 576px) {
  nav {
    height: 64px;
  }
}
</style>
