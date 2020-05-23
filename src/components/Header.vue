<template>
  <div id="header">
    <div id="menu">
      <img src="../assets/log.png" alt="logo">
      <ul>
        <li>Home</li>
        <li>About ass</li>
        <li>Services</li>
        <li>Contact</li>
        <li>Login</li>
      </ul>
    </div>
    <h1>WELCOME TO PINK</h1>
    <h2>A multi purpose theme from cssauthor.com</h2>
  </div>
</template>

<script>
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
  }

</script>

<style scoped>
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
    margin-left: 7%;
    font-size: 140%;
  }

  h1 {
    color: white;
    margin-top: 25%;
    margin-left: 30%;
    font-size: 480%;
    height: 7%;
  }

  h2 {
    color: white;
    margin-left: 35%;
    font-size: 180%;
    margin-top: 5%;
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
      height: 30%;
    }
  }

  @media screen and (min-width:760px) and (max-width:1023px) {
    #menu {
      height: 45%;
    }

    img {
      height: 30%;
    }
  }

  @media screen and (min-width:1024px) and (max-width:1370px) {
    img {
      margin: 20px 100px 10px;
    }

    ul {
      width: 90%;
      margin-right: 5%;
    }
  }

  /*optimizatiom*/

</style>
