<template>
  <div>
    <h2 class="m-3 text-center ">About Me</h2>
    <p class="fs-4 m-2">

      Mom of 5, previous photographer and CEO of Floyd Family Photography, avid outdoor adventurer, Heather is a newly
      reinvented software developer. She is excited to work front end applications in order to help businesses sell
      their
      products effectively and efficiently. Making beautiful designs functional to move businesses toward their goals,
      is her desire and ambition.
    </p>
    <div class="btn d-flex justify-content-center">
      <button class="m-3" @click="sendEmail()">
        Contact Heather
      </button>
    </div>
    <hr class="m-3">
    <p class="m-3 text-center fs-2 ">
      <a href="https://www.linkedin.com/in/heathermjohnsonwebdev/"><i class="mdi mdi-linkedin"></i></a>
    </p>
  </div>
</template>


<script>
export default {
  setup() {
    function sendEmail() {
      window.location = "mailto:heathermjohnsonwebdev@gmail.com";

    }
    return {
      sendEmail

    }
  }
}
</script>


<style lang="scss" scoped>
.font {
  font-family: "Shadows Into Light", cursive;
  font-weight: 400;
  font-style: normal;
  font-size: 75px;
}
</style>