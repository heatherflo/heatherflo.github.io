<template>

  <div class="font col-12">

    <p class="text-center m-3">Applications</p>
  </div>


  <div class="row">
    <div class="col-12 col-md-4 ">
      <div class="image-container" @mouseover="showText('keepr')" @mouseleave="hideText('keepr')">
        <a href="https://keepr.heathermaejohnson.com">
          <img class="img-fluid hover" src="/img/keepr.png" alt="">
          <div class="hover-text font" v-show="showKeepr">Keepr</div>
        </a>
      </div>
    </div>
    <div class="col-12 col-md-4">
      <div class="image-container" @mouseover="showText('tower')" @mouseleave="hideText('tower')">
        <a href="https://tower.heathermaejohnson.com">
          <img class="img-fluid hover" src="/img/tower.png" alt="">
          <div class="hover-text font" v-show="showTower">Tower</div>
        </a>
      </div>
    </div>
    <div class="col-12 col-md-4">
      <img class="img-fluid hover" src="/img/potholes.jpg" alt="">
    </div>


  </div>

</template>


<script>
export default {
  data() {
    return {
      showKeepr: false,
      showTower: false,
    }
  },
  methods: {
    showText(image) {
      this[`show${image.charAt(0).toUpperCase() + image.slice(1)}`] = true;
    },
    hideText(image) {
      this[`show${image.charAt(0).toUpperCase() + image.slice(1)}`] = false;
    }
  }
};
</script>


<style lang="scss" scoped>
.hover {
  height: 40vh;
  width: auto;
}

img {
  opacity: 1.0;
}

img:hover {
  opacity: 0.5;
}

.font {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 50px;
}

.image-container {
  position: relative;
}

.hover-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateX(-50%);
  // background-color: rgba(255, 255, 255, 0.8);
  padding: 5px;
  border-radius: 5px;
  display: none;
}

.image-container:hover .hover-text {
  display: block;
}
</style>