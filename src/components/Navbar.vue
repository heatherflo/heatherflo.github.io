<template>
  <nav class="container-fluid">
    <div class="col-12">
      <router-link class="" :to="{ name: 'HomePage' }">
        <img class="img-fluid logo" src="/src/assets/img/HJ.jpg" alt="HJ logo ">

      </router-link>
      <router-link class="font " :to="{ name: 'AboutPage' }">
        About Me
      </router-link>
      <p class="font">UX Design</p>
      <p class="font">Photos</p>
    </div>

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
  color: black;
}

.logo {
  max-width: 30px;
  max-height: 30px;
  color: black;
}

@media screen and (min-width: 576px) {
  nav {
    height: 64px;
  }
}
</style>
