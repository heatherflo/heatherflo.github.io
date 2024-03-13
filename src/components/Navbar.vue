<template>
  <nav class="container-fluid navbar navbar-expand-sm navbar-dark bg-light px-3 col-12 font   ">


    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">

      <div class="text-dark fs-2 ">Heather Johnson</div>
    </router-link>
    <!-- <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
      aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">
        <li>
          <router-link :to="{ name: 'About' }" class="btn fs-4 text-dark lighten-30 selectable ">
            Portfolio
          </router-link>
          <router-link :to="{ name: 'About' }" class="btn fs-4 text-dark lighten-30 selectable">
            About
          </router-link>
          <router-link :to="{ name: 'About' }" class="btn fs-4 text-dark lighten-30 selectable">
            Contact
          </router-link>
        </li>
      </ul>

    </div> -->
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
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  /* border-bottom: 2px solid var(--bs-success); */
  border-bottom: 2px solid black;
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

.font {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
}

@media screen and (min-width: 576px) {
  nav {
    height: 64px;
  }
}
</style>
