<template>
  <div>
    <section id="first-footer-section">
      <div class="container centralized-item">
        <div class="lists-wrapper centralized-item">
          <div>
          <h2 class="my-text-white">DC COMICS</h2>
          <nav>
            <ul class="footer-list">
              <li v-for="(link, index) in dcComics" :key="index">
                <a href="#">{{ link.link }}</a> 
              </li>
            </ul>
          </nav>
          <!-- SHOP DC -->
          <h2 class="my-text-white">SHOP</h2>
          <nav>
            <ul class="footer-list">
              <li v-for="(link, index) in dcShop" :key="index">
                <a href="#">{{ link.link }} </a> 
              </li>
            </ul>
          </nav>
        </div>
        <div>
          <h2 class="my-text-white">DC</h2>
          <nav>
            <ul class="footer-list">
              <li v-for="(link, index) in dcTerms" :key="index">
                <a href="#">{{ link.link }}</a> 
              </li>
            </ul>
          </nav>
        </div>
        <div>
          <h2 class="my-text-white">SITES</h2>
          <nav>
            <ul class="footer-list">
              <li v-for="(link, index) in dcSites" :key="index">
                <a href="#">{{ link.link }}</a> 
              </li>
            </ul>
          </nav>
        </div>
        </div>
        <div id="logo-bg">
        </div>
      </div>
      
    </section>
    <section id="last-footer-section">
      <div class="container centralized-item">
        <div>
          <button>SIGN-UP NOW!</button>
        </div>
        <div class="social-wrapper centralized-item">
          <h2>FOLLOW US</h2>
          <nav>
            <ul class="footer-list centralized-item">
              <li>
                <a href="#">
                  <img src="../assets/img/footer-facebook.png" alt="facebook logo">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="../assets/img/footer-twitter.png" alt="twitterlogo">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="../assets/img/footer-youtube.png" alt="youtube logo">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="../assets/img/footer-pinterest.png" alt="pintarest logo">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="../assets/img/footer-periscope.png" alt="periscope logo">
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexFooter',
  data: function(){
    return{
      dcComics: [
        {
          link: 'Characters'
        },
        {
          link: 'Comics'
        },
        {
          link: 'Movies'
        },
        {
          link: 'TV'
        },
        {
          link: 'Games'
        },
        {
          link: 'Videos'
        },
        {
          link: 'News'
        },
      ],
      dcShop: [
        {
          link: 'Shop'
        },
        {
          link: 'Shop DC Collectibles'
        },
      ],
      dcTerms: [
        {
          link: 'Terms of use'
        },
        {
          link: 'Privacy of policy (News)' 
        },
        {
          link: 'Ad Choising'
        },
        {
          link: 'Advertising'
        },
        {
          link: 'Jobs'
        },
        {
          link: 'Subscription'
        },
        {
          link: 'Talent Workshop'
        },
        {
          link: 'CPSP Certificates'
        },
        {
          link: 'Rating'
        },
        {
          link: 'Shop Help'
        },
        {
          link: 'Contact us'
        },
      ],
      dcSites: [
        {
          link: 'DC'
        },
        {
          link: 'MAD'
        },
        {
          link: 'Magazine'
        },
        {
          link: 'DC Kids'
        },
        {
          link: 'DC Universe'
        },
        {
          link: 'DC Power Visa'
        },
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/scss/partials/_variables.scss";
#first-footer-section{
  background-image: url("../assets/img/footer-bg.jpg");
  .lists-wrapper{
    justify-content: start;
    align-items: flex-start;
    div{
      padding-right: 1rem;
    }
  }
  #logo-bg{
    background-image: url("../assets/img/dc-logo-bg.png");
    height: 23rem;
    width: 70%;
    background-position: center;
    background-repeat: no-repeat;
  }
}
#last-footer-section{
  background-color: #303030;
  padding: 2rem 0;
  button{
    font-size: 1.2rem;
    background-color: #303030;
    color: white;
    text-decoration: none;
    border: 2px solid $brandColor;
    padding: 1.2rem;
  }
  .social-wrapper{
    h2{
      color: $brandColor;
    }
  }
  .footer-list{
    li{
      margin: 0 .4rem;
    }
  }
}
</style>
