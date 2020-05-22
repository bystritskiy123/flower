<template>
  <div id="app">
    <Header />
    <Second />
    <gallery />
    <last />
  </div>
</template>

<script>
  import Header from './components/Header'
  import Second from './components/Second'
  import gallery from './components/gallery'
  import last from './components/footer'
  export default {
    name: 'app',
    data() {
      return {

      }
    },
    components: {
      Header,
      Second,
      gallery,
      last
    }
  }

</script>

<style scoped>

</style>
