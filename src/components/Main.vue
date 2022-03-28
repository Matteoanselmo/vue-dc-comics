<template>
  <div>
    <section id="main-content" >
      <div class="container">
        <h1>Content goes here </h1>
      </div>
    </section>
    <section id="card-section">
      <div class="container centralized-item">
        <div class="centralized-item card-wrapper">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics card">
          <p>digital comics</p>
        </div>
        <div class="centralized-item card-wrapper">
          <img src="../assets/img/buy-comics-merchandise.png" alt="digital merchandise">
          <p>dc merchandise</p>
        </div>
        <div class="centralized-item card-wrapper">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="digital comics subscription">
          <p>subscription</p>
        </div>
        <div class="centralized-item card-wrapper">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="digital comics shop locator">
          <p>comic shop locator</p>
        </div>
        <div class="centralized-item card-wrapper">
          <img class="my-svg-card" src="../assets/img/buy-dc-power-visa.svg" alt="digital comics card">
          <p>dc power visa</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexMain'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/scss/partials/_variables.scss";
#main-content{
  background-color: black;
  color: white;
  padding: 4rem 0;
}
#card-section{
  background-color: $brandColor;
  padding: 2rem 0;
  img{
    width: 25%;
  }
  p{
    color: white;
    text-transform: uppercase;
  }
  .card-wrapper{
    justify-content: space-evenly;
    .my-svg-card{
      width: 7rem;
    }
  }
}

</style>
