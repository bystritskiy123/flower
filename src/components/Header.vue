<template>
  <div id="header">
    <div id="menu">
      <img src="../assets/log.png" alt="logo">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About ass</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">
            <forma /></a></li>
      </ul>
    </div>
    <h1>WELCOME TO PINK</h1>
    <h2>A multi purpose theme from cssauthor.com</h2>
  </div>
</template>

<script>
  import forma from './forma.vue'
  export default {
    name: 'Header',
    data() {
      return {

      }
    },

    methods: {

    },
    computed: {

    },

    components: {
      forma
    }
  }

</script>

<style scoped>
  @font-face {
    font-family: 'AlteHaasGroteskBold';
    src: url('../fonts/AlteHaasGroteskBold.ttf') format("truetype");
  }

  @font-face {
    font-family: 'univers';
    src: url('../fonts/univers.ttf') format("truetype");
  }

  #header {
    background-image: url('../assets/backgraund.png');
    background-size: cover;
    width: 100%;
    height: 45rem;
  }

  #menu {
    background-color: rgba(255, 255, 255, 0.767);
    background-size: cover;
    width: auto;
    height: 17%;
    display: flex;
  }

  img {
    width: auto;
    height: 70%;
    margin: 20px 200px 15px;
  }

  ul {
    display: flex;
    list-style-type: none;
    width: 50%;
    height: auto;
    margin-top: 3%;
  }

  li {
    margin-left: 8%;
    font-size: 120%;
  }

  li a {
    text-decoration: none;
    color: black;
  }

  h1 {
    color: white;
    margin-top: 25%;
    margin-left: 30%;
    font-size: 480%;
    height: 7%;
    font-family: 'AlteHaasGroteskBold';
  }

  h2 {
    color: white;
    margin-left: 35%;
    font-size: 180%;
    margin-top: 5%;
    font-family: 'univers';
  }

  button {
    border-radius: 4px 4px 4px 4px;
    background-color: red;
    color: white;
  }

  /*optimization*/
  @media screen and (max-width:850px) {
    img {
      width: auto;
      height: 40%;
      margin: 20px 20px 10px;
    }

    ul {
      display: block;
    }

    li {
      margin-top: 5%;
    }

    #menu {
      height: 35%;
    }

    h1 {
      font-size: 200%;
      margin-left: 7%;
      margin-top: 40%;
    }

    h2 {
      margin-left: 6%;
      font-size: 100%;
    }
  }

  @media screen and (min-width:760px) and (max-width:1023px) {
    #header {
      height: 50rem;
    }


    #menu {
      height: 20%;
    }

    img {
      width: 35%;
      height: 50%;
      margin: 30px;
    }

    ul {
      display: flex;
      width: 100%;
      height: auto;
    }

    li {
      font-size: 120%;
      margin-left: 5%;
    }

    h1 {
      font-size: 330%;
      margin-top: 30%;
      margin-left: 30%;
    }

    h2 {
      margin-left: 30%;
      font-size: 160%;
    }
  }

  @media (min-width:1024px) and (max-width:1370px) {
    img {
      margin: 20px 100px 10px;
    }

    ul {
      width: 90%;
      margin-right: 5%;
    }

    h1 {
      font-size: 370%;
      margin-left: 35%;
    }
  }

  @media (min-width:1920px) {
    #header {
      height: 58rem;
    }

    ul {
      margin-left: 5%;
    }

    li {
      font-size: 200%;
    }

    h1 {
      font-size: 700%;
      margin-left: 25%;
      margin-top: 24%;
    }

    h2 {
      font-size: 250%;
      margin-left: 32%;
    }
  }

  @media (min-width:2500px) and (max-width:5000px) {
    #header {
      height: 77rem;
    }

    img {
      width: auto;
      height: 80%;
      margin: 20px 300px 15px;
    }

    ul {
      margin-top: 3%;
    }

    li {
      font-size: 220%;
    }

    h1 {
      font-size: 900%;
    }

    h2 {
      font-size: 300%;
    }
  }

  /*optimizatiom*/

</style>
