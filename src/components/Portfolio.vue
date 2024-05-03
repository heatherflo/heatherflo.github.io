<template>





  <div class="font col-12">

    <p class="text-center m-3">Applications</p>
  </div>


  <div class="row">
    <div class="col-12 col-md-4 ">
      <a href="https://keepr.heathermaejohnson.com">
        <img class="img-fluid hover" src="/img/keepr.png" alt="">

      </a>
    </div>
    <div class="col-12 col-md-4">
      <a href="https://tower.heathermaejohnson.com">
        <img class="img-fluid hover" src="/img/tower.png" alt="">
      </a>
    </div>
    <div class="col-12 col-md-4">
      <img class="img-fluid hover" src="/img/potholes.jpg" alt="">
    </div>


  </div>

</template>


<script>
export default {
  setup() {
    return {}
  }
};
</script>


<style lang="scss" scoped>
.hover {
  height: 40vh;
  width: auto;
}

img {
  opacity: 0.5;
}

img:hover {
  opacity: 1.0;
}

// :hover {
//   color:
// }

.font {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 50px;
}
</style>