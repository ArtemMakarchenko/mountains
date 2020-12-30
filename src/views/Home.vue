<template>
  <v-container
    fluid
    id="home"
    class="d-flex justify-center align-center white--text display-3 text-uppercase"
  >
    <v-row class="col-6">
        <h1 class="col-12" color="white">Do you whant to see?</h1>
          <!-- <svg style="width:24px;height:24px" viewBox="0 0 24 24" class="col-12">
          <path fill="currentColor"
          d="M11,4H13V16L18.5,10.5L19.92,11.92L12,19.84L4.08,11.92L5.5,10.5L11,16V4Z" />
          </svg> -->
        <v-btn
          class="mt-6 display-1 pa-8 col-12"
          outlined
          color="white"
          rounded
          large
        >
          Mountains
        </v-btn>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'Home',

  data: () => ({
  }),
};
</script>

<style lang="scss" scope>
  #home{
    height: 100vh;
    background: url(https://s1.1zoom.me/big0/421/343461-svetik.jpg) no-repeat;
    background-position: top center;
    background-size: cover;
  }
  h1{
    line-height: 120px;
    text-shadow: 0px 0px 3px #b9b9b9;
  }
</style>
