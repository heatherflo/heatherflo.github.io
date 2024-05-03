<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col center">
        <img class="img" src="/src/assets/img/backpack.jpg" alt="">
        <img class="img" src="/src/assets/img/boardwalk.jpg" alt="">
        <img class="img" src="/src/assets/img/brian.jpg" alt="">
        <img class="img" src="/src/assets/img/crators.jpg" alt="">
        <img class="img" src="/src/assets/img/hiddensprings.jpg" alt="">
        <img class="img" src="/src/assets/img/camp.jpg" alt="">
        <img class="img" src="/src/assets/img/ladies.jpg" alt="">
        <img class="img" src="/src/assets/img/kenz.jpg" alt="">
      </div>
    </div>

  </div>
</template>


<script>
import { AppState } from '../AppState';
import { computed, ref, onMounted } from 'vue';
export default {
  setup() {
    return {}
  }
};
</script>


<style lang="scss" scoped>
.img {
  object-fit: center;
  width: 400px;
  height: 300px;
  margin: 0%;
}

.center {

  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>