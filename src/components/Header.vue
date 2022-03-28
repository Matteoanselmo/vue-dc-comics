<template>
  <div id="index-header">
    <div class="container centralized-item">
      <img src="../assets/img/dc-logo.png" alt="dc logo">
      <nav>
        <ul>
          <li v-for="(link, index) in linkInfo" :key="index" class="active">
            <a :href="link.url">{{ link.name }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexHeader',
  data: function(){
    return{
      linkInfo: [
        {
          name: 'CHARACTER',
          url: '#',
          tap: false
        },
        {
          name: 'COMICS',
          url: '#',
          tap: false
        },
        {
          name: 'MOVIES',
          url: '#',
          tap: false
        },
        {
          name: 'TV',
          url: '#',
          tap: false
        },
        {
          name: 'GAMES',
          url: '#',
          tap: false
        },
        {
          name: 'COLLECTIBLES',
          url: '#',
          tap: false
        },
        {
          name: 'VIDEOS',
          url: '#',
          tap: false
        },
        {
          name: 'FANS',
          url: '#',
          tap: false
        },
        {
          name: 'NEWS',
          url: '#',
          tap: false
        },
        {
          name: 'SHOP',
          url: '#',
          tap: false
        },
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
  #index-header{
    background-color: aliceblue;
    // padding: 1rem;
  }
  ul{
    display: flex;
    li{
      list-style-type: none;
      padding: 3.5rem .5rem;
      &:hover{
        border-bottom: 5px solid $brandColor;
      }
      a{
        font-weight: 600;
        text-decoration: none;
        color: black;
      &:active,
      &.active{
        color: $brandColor;
        }
      }
    }
  }

</style>
