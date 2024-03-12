<template>
  




  <div class="font col-12">

    <p class="text-center m-3">Applications</p>
  </div>
  <hr class="m-3">
<div class="d-flex col justify-content-center  ">

  <div class="card selectable mx-2">
        <p class="fs-4 p-2 text-center">Keepr</p>

        <img class=" img-fluid keepr" :src="'/src/assets/img/keepr.png'" alt="screenshot of KeeprAp">
      </div>
    
      <div class="card selectable mx-2">

        <p class="fs-4 p-2 text-center">allSpice</p>
        <img class=" img-fluid keepr" :src="'/src/assets/img/allSpice.png'" alt="screenshot of KeeprAp">
    
      </div>

      <div class="card selectable mx-2">

        <p class="fs-4 p-2 text-center">Tower</p>
        <img class=" img-fluid keepr" :src="'/src/assets/img/tower.png'" alt="screenshot of KeeprAp">
      </div>
      <div class="card selectable mx-2">
        <p class="fs-4 p-2 text-center">theNetwork</p>

        <img class=" img-fluid keepr" :src="'/src/assets/img/theNetwork.png'" alt="screenshot of KeeprAp">
      </div>
  </div>

<section class="row">
  <div class="font">

<p class="m-3 text-center m-3">Pictures</p>
</div>

<!-- carrousel -->


  <div id="portfolio" class="carousel slide carousel-dark" data-bs-ride="carousel">
    <div class="carousel-inner">
      <!-- <div class="carousel-item active">
        <img src="src/assets/img/backpack.jpg" class="d-block w-75" alt="...">
      </div> -->
      <div class="carousel-item">
        <img src="/src/assets/img/bluelake.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/boardwalk.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/brian.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/camp.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/crators.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/hiddensprings.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/kenz.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/ladies.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/Leslie.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/leslie2.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/mountain.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/ocean.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/ocean2.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/potholes.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/towels.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/trees.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item">
        <img src="/src/assets/img/winter.jpg" class="d-block w-95" alt="...">
      </div>
      <div class="carousel-item ">
        <img src="/src/assets/img/yosemite.jpg" class="d-block w-95" alt="...">
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
  </div>


</section>

      

    

  
</template>


<script>

export default {
  setup() {
    return {}
  }
};
</script>


<style lang="scss" scoped>



.keepr{
  height: 20vh;
  width: auto;
}
.font{
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 75px;
}

</style>