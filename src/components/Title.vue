<template>

<div class="col-12 portfolio d-flex flex-column justify-content-center align-items-center ">
<div>
  <img class="img-fluid me" :src="'/src/assets/img/me2.jpeg'" alt="self portrait of Heather Johnson">
</div>
<div class="name">
Heather Johnson
</div>

<div>
  Software Developer | Photographer
</div>

</div>
</template>


<script>
export default {
setup(){
return{}
}
}
</script>


<style lang="scss" scoped>
.portfolio{
  height: 80vh;
  background-color: #43c5b8;
  width: 100%;
}

.me {
  object-fit: cover;
  border-radius: 50%;
  width: 350px;
  height: 350px;
}
.name {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 100px;
}
.keepr{
  height: 20vh;
  width: auto;
}
</style>