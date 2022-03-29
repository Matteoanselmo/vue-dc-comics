<template>
  <div class="main-card">
    <img :src="cardImage" :alt="cardText">
    <p>{{cardText}}</p>
  </div>
</template>

<script>
export default {
  name: 'PropetiesCard',
  props: ['cardImage' , 'cardText']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  .main-card{
    height: 300px;
    width: calc(100% / 6);
    padding: .5rem;
    text-align: start;
    cursor: pointer;
    p{
      text-transform: uppercase;
    }
    p,img{
      margin-bottom: .8rem;
    }
    img{
      height: 90%;
      object-fit: none;
      object-position: top;
    }
  }
</style>
