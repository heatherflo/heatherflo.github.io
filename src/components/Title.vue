<template>

  <div class="col-12 portfolio d-flex flex-column justify-content-center align-items-center ">

    <div class="name text-center">
      Heather Johnson
    </div>

    <div class="fs-2">
      Software Developer
    </div>
    <div class="fs-3">
      Motivated full-stack software developer. Ready to drive business success.

    </div>

  </div>
</template>


<script>
export default {
  setup() {
    return {}
  }
}
</script>


<style lang="scss" scoped>
.portfolio {
  height: 30vh;
  width: 100%;
}

.me {
  object-fit: cover;
  border-radius: 50%;
  width: 300px;
  height: 300px;
}

.name {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 50px;
}

.keepr {
  height: 20vh;
  width: auto;
}
</style>