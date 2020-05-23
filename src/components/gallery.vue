<template>
  <div id="gallery">
    <hr>
    <!--1-->
    <div class="card mb-3">
      <div class="row no-gutters">
        <div class="col-md-4">
          <img src="../assets/Layer 5 copy 2.png" class="card-img" alt="photo">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Lorem Ipsum is simply </h5>
            <p class="card-text">orem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an
              unknown printer took a galley of type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into electronic typesetting, remaining
              essentially unchanged.
            </p>
          </div>
        </div>
      </div>
    </div>
    <!--1-->
    <!--2-->
    <div class="card mb-3">
      <div class="row no-gutters">
        <div class="col-md-4">
          <img src="../assets/Layer 5 copy 2.png" class="card-img" alt="photo">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Lorem Ipsum is simply </h5>
            <p class="card-text">orem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an
              unknown printer took a galley of type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into electronic typesetting, remaining
              essentially unchanged.
            </p>
          </div>
        </div>
      </div>
    </div>
    <!--2-->
    <!--3-->
    <div class="card mb-3">
      <div class="row no-gutters">
        <div class="col-md-4">
          <img src="../assets/Layer 5 copy 2.png" class="card-img" alt="photo">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Lorem Ipsum is simply </h5>
            <p class="card-text">orem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an
              unknown printer took a galley of type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into electronic typesetting, remaining
              essentially unchanged.
            </p>
          </div>
        </div>
      </div>
    </div>
    <!--3-->
  </div>
</template>

<script>
  export default {
    name: 'gallery',
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
  #gallery {
    margin-top: 8%;
  }

  .card {
    width: 70%;
    height: auto;
    margin-left: 20%;
    margin-top: 9%;
    border: 0px;
  }

  hr {
    margin-top: 10%;
  }

  /*optimization*/
  @media (min-width:768px) and (max-width:1023px) {
    .card-img {
      margin-top: 15%;
    }
  }

  @media (min-width:1024px) and (max-width:1366px) {
    .card-img {
      margin-top: 15%;
    }
  }

</style>
