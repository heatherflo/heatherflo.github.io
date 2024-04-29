<template>
  <nav class="container-fluid">
    <div class="col-12 d-flex">
      <router-link :to="{ name: 'Home' }">
        <img class="img-fluid logo m-2" src="/src/assets/img/HJ.jpg" alt="HJ logo ">
      </router-link>

      <router-link :to="{ name: 'UX Design' }">

        <div class="font fs-2 m-2">UX Design</div>
      </router-link>

      <router-link :to="{ name: 'Photos' }">

        <div class="font fs-2 m-2">Photos</div>
      </router-link>

      <router-link :to="{ name: 'About' }">
        <div class="font fs-2 m-2 ">About Me</div>
      </router-link>


    </div>

  </nav>
</template>

<script>

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
  max-width: 40px;
  max-height: 40px;
  color: black;
}

@media screen and (min-width: 576px) {
  nav {
    height: 64px;
  }
}
</style>
