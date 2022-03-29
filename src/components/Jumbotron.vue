<template>
  <div id="jumbo">

  </div>
</template>

<script>
export default {
  name: 'IndexJumbotron',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/scss/partials/_variables.scss";
#jumbo{
  height: 45vh;
  background-image: url('http://localhost:8080/img/jumbotron.dac2f96c.jpg');
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
