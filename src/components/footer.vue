<template>
  <div id="footer">
    <!--Начало-->
    <div class="col-md-12 row">
      <div id="part_1" class="col-md-7">
        <div class="text">
          <h3>Sub Menu</h3>
          <a href="#">
            <h4 class="first">Android</h4>
          </a>
          <a href="#">
            <h4> Apps</h4>
          </a>
          <a href="#">
            <h4>Articles</h4>
          </a>
          <a href="#">
            <h4>Backgrounds</h4>
          </a>
          <a href="#">
            <h4>Blogger</h4>
          </a>
          <a href="#">
            <h4> Books</h4>
          </a>
          <a href="#">
            <h4>Coding</h4>
          </a>
        </div>
        <div class="text">
          <h3>Sub Menu</h3>
          <a href="#">
            <h4 class="first">Freebies</h4>
          </a>
          <a href="#">
            <h4>Greetings</h4>
          </a>
          <a href="#">
            <h4>Icons</h4>
          </a>
          <a href="#">
            <h4>Illustrator</h4>
          </a>
          <a href="#">
            <h4>Inspiration</h4>
          </a>
          <a href="#">
            <h4>iPad</h4>
          </a>
          <a href="#">
            <h4>iPhone</h4>
          </a>
        </div>
        <div class="text">
          <h3>Sub Menu</h3>
          <a href="#">
            <h4 class="first">Drupal</h4>
          </a>
          <a href="#">
            <h4>Fonts</h4>
          </a>
          <a href="#">
            <h4>Freebies</h4>
          </a>
          <a href="#">
            <h4>Greetings</h4>
          </a>
          <a href="#">
            <h4>Icons</h4>
          </a>
          <a href="#">
            <h4>Illustrator</h4>
          </a>
          <a href="#">
            <h4>Inspiration</h4>
          </a>
        </div>
        <div class="text">
          <h3>Sub Menu</h3>
          <a href="#">
            <h4 class="first">JQuery</h4>
          </a>
          <a href="#">
            <h4> Magento</h4>
          </a>
          <a href="#">
            <h4> Mobile</h4>
          </a>
          <a href="#">
            <h4> Photoshop</h4>
          </a>
          <a href="#">
            <h4>Plugins</h4>
          </a>
          <a href="#">
            <h4>Resource</h4>
          </a>
          <a href="#">
            <h4>Templates</h4>
          </a>
        </div>
      </div>
      <div id="part_2" class="col-md-5">
        <div class="img">
          <a href="#"><img src="../assets/facebook.png" alt="one"></a>
          <a href="#"><img src="../assets/twitter.png" alt="two"></a>
          <a href="#"><img src="../assets/dribbble.png" alt="three"></a>
          <a href="#"><img src="../assets/share.png" alt="four"></a>
        </div>
        <h4>Copyright © 2009–2013 Cssauthor.com</h4>
      </div>
    </div>
    <!--Конец-->
  </div>
</template>

<script>
  export default {
    name: 'Last',
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
  #footer {
    display: flex;
    margin-top: 10%;
    background: rgba(0, 0, 0, 0.753);
    background-size: cover;
    width: auto;
    height: auto;
    font-family: 'univers';
  }

  #part_1 {
    display: flex;
    width: 50%;
    height: auto;
  }

  #part_1 .text {
    margin-left: 8%;
    margin-top: 5%;
  }

  #part_1 .text h3 {
    color: white;
  }

  #part_1 .text a {
    color: white;
    text-decoration: none;
  }

  #part_1 .text .first {
    margin-top: 20%;
  }

  #part_2 {
    margin-top: 6%;
  }

  #part_2 a {
    margin-left: 10%;
  }

  #part_2 h4 {
    margin-top: 5%;
    margin-left: 8%;
    color: white;
  }

  /*optimization*/
  @media (min-width:300px) and (max-width:820px) {
    #part_1 h4 {
      font-size: 93%;
    }

    #part_2 img {
      width: 10%;
      margin-left: 3%;
    }

    #part_2 h4 {
      font-size: 90%;
      margin-left: 13%;
    }
  }

  @media (min-width:1024px) and (max-width:1366px) {
    #part_1 .text h3 {
      font-size: 150%;
    }

    #part_2 .img {
      width: 98%;
      margin-left: 13%;
    }

    #part_2 h4 {
      margin-left: 30%;
    }
  }

  @media screen and (min-width:1920px) {
    #part_1 .text h3 {
      font-size: 220%;
    }

    #part_1 .text h4 {
      font-size: 170%;
    }

    #part_2 img {
      width: 10%;
    }

    #part_2 h4 {
      font-size: 220%;
    }
  }

</style>
