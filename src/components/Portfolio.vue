<template>





  <div class="font col-12">

    <p class="text-center m-3">Applications</p>
  </div>


  <div class="row">

    <img class="img-fluid keepr" src="/img/keepr.png" alt="">
    <div class="col-4"
      :style="{ backgroundImage: 'src/assets/img/keepr.png', height: '45vh', backgroundPosition: 'cover' }">

      <div class=" d-flex text-box flex-column align-items-start justify-content-end">
        <h3 class="text-dark">Hover text</h3>

      </div>
    </div>

  </div>




  <div class="d-flex col-12 justify-content-center  ">
    <a href="https://keepr.heathermaejohnson.com">

      <div class="card selectable mx-2">
        <p class="fs-4 p-2 text-center">Keepr</p>

        <img class=" img-fluid keepr" src="/img/keepr.png" alt="screenshot of KeeprAp">
      </div>
    </a>




    <!-- <div class="card selectable mx-2">

      <p class="fs-4 p-2 text-center">allSpice</p>
      <img class=" img-fluid keepr" src="/img/allSpice.png" alt="screenshot of KeeprAp">

    </div> -->
    <a href="https://tower.heathermaejohnson.com">

      <div class="card selectable mx-2">

        <p class="fs-4 p-2 text-center">Tower</p>
        <img class=" img-fluid keepr" src="/img/tower.png" alt="screenshot of TowerAp">
      </div>
    </a>
    <!-- <div class="card selectable mx-2">
      <p class="fs-4 p-2 text-center">theNetwork</p>

      <img class=" img-fluid keepr" src="/img/theNetwork.png" alt="screenshot of KeeprAp">
    </div> -->
  </div>
  <!-- <hr class="m-3"> -->

  <!-- <section class="row">
    <div class="font">

      <p class="m-3 text-center m-3">Pictures</p>
    </div> -->

  <!-- carrousel -->


  <!-- <div id="portfolio" class="carousel slide carousel-dark" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
        <img src="src/assets/img/backpack.jpg" class="d-block w-75" alt="...">
      </div>
        <div class="carousel-item active">
          <img src="/img/bluelake.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/boardwalk.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/brian.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/camp.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/crators.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/hiddensprings.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/kenz.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/ladies.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/Leslie.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/leslie2.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/mountain.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/ocean.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/ocean2.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/potholes.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/towels.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/trees.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/img/winter.jpg" class="d-block w-95" alt="...">
        </div>
        <div class="carousel-item ">
          <img src="/img/yosemite.jpg" class="d-block w-95" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev text-dark" type="button" data-bs-target="#portfolio" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#portfolio" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div> -->


  <!-- </section> -->






</template>


<script>
export default {
  setup() {
    return {}
  }
};
</script>


<style lang="scss" scoped>
.keepr {
  height: 20vh;
  width: auto;
}

// :hover {
//   color:
// }

.font {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 75px;
}
</style>