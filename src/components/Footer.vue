<template>
  <div>
    <section id="first-footer-section">
      <div class="container centralized-item">
        <div class="lists-wrapper centralized-item">
          <div>
          <h2 class="my-text-white">DC COMICS</h2>
          <nav>
            <ul class="footer-list">
              <li>
                <a href="#">Characters</a> 
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Videos</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
            </ul>
          </nav>
          <h2 class="my-text-white">SHOP</h2>
          <nav>
            <ul class="footer-list">
              <li>
                <a href="#">Shop DC </a> 
              </li>
              <li>
                <a href="#">Shop DC Collectibles</a>
              </li>
            </ul>
          </nav>
        </div>
        <div>
          <h2 class="my-text-white">DC</h2>
          <nav>
            <ul class="footer-list">
              <li>
                <a href="#">Terms of use</a> 
              </li>
              <li>
                <a href="#">Privacy Policy (News)</a>
              </li>
              <li>
                <a href="#">Ad Choising</a>
              </li>
              <li>
                <a href="#">Advertising</a>
              </li>
              <li>
                <a href="#">Jobs</a>
              </li>
              <li>
                <a href="#">Subscription</a>
              </li>
              <li>
                <a href="#">Talent Workshop</a>
              </li>
              <li>
                <a href="#">CPSC Certificates</a>
              </li>
              <li>
                <a href="#">rating</a>
              </li>
              <li>
                <a href="#">Shop Help</a>
              </li>
              <li>
                <a href="#">Contact Us</a>
              </li>
            </ul>
          </nav>
        </div>
        <div>
          <h2 class="my-text-white">SITES</h2>
          <nav>
            <ul class="footer-list">
              <li>
                <a href="#">DC</a> 
              </li>
              <li>
                <a href="#">MAD Magazine</a>
              </li>
              <li>
                <a href="#">DC Kinds</a>
              </li>
              <li>
                <a href="#">DC Universe</a>
              </li>
              <li>
                <a href="#">DC Power Visa</a>
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
  name: 'IndexFooter'
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
