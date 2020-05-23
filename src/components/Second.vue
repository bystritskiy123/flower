<template>
  <div id="Second">
    <h1>lorem ipsum is simply dummy</h1>
    <h3>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the indus-</h3>
    <h4>try's standard dummy text ever since the 1500s, when an unknown</h4>
    <div id="images">
      <img src="../assets/Tickets.png" alt="Tickets">
      <img src="../assets/Camera.png" alt="Camera">
      <img src="../assets/bear.png" alt="bear">
      <img src="../assets/Devices.png" alt="Devices">
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Second',
    data() {
      return {

      }
    },

    methods: {

    },
    computed: {

    }
  }

</script>

<style scoped>
  h1 {
    margin-left: 30%;
    margin-top: 10%;
    font-size: 300%;
  }

  h3 {
    width: 82%;
    height: auto;
    font-size: 150%;
    margin-left: 10%;
    margin-top: 2%;
  }

  h4 {
    margin-left: 25%;
  }

  #images {
    width: auto;
    height: auto;
    margin-left: 15%;
    margin-top: 10%;
  }

  img {
    margin-left: 5%;
  }

  /*optimization*/
  @media (min-width:360px) and (max-width:850px) {
    h1 {
      margin-left: 10%;
    }

    h4 {
      margin-left: 10%;
    }

    img {
      margin-left: 17%;
      margin-top: 7%;
    }
  }

</style>
