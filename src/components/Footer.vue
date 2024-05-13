<template>
  <nav class="container-fluid">
    <div class="row">

      <div class="col-10 d-flex justify-content-end">
        <a href="https://instagram.com/mmsgoadventure"><i class="mdi mdi-instagram"></i></a>

        <a href="https://github.com/heatherflo"><i class="mdi mdi-github"></i></a>

        <a href="https://www.linkedin.com/in/heathermjohnsonwebdev/"><i class="mdi mdi-linkedin"></i></a>
      </div>
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
