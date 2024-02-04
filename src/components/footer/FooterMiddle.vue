<template>
    <section>
        <div class="container">
            <div class="row">

              <!-- 1 column -->
              <div class="col-auto">
                <h5>DC COMICS</h5>
                <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">Games</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">News</a></li>
                </ul>
                
                <h5>SHOP</h5>
                <ul>
                  <li><a href="#">Shop DC</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
              </div>
              
              <!-- 2 column -->
              <div class="col-auto">
                <h5>DC</h5>
                <ul>
                  <li><a href="#">Terms Of Use</a></li>
                  <li><a href="#">Privacy policy (New)</a></li>
                  <li><a href="#">Ad Choices</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Jobs</a></li>
                  <li><a href="#">Subscriptions</a></li>
                  <li><a href="#">Talent Workshops</a></li>
                  <li><a href="#">CPSC Certificares</a></li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Us</a></li>
                </ul>
              </div>
              
              <!-- 3 column -->
              <div class="col-auto">
                <h5>SITES</h5>
                <ul>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Universe</a></li>
                  <li><a href="#">DC Power VIsa</a></li>
                </ul>
              </div>
            </div>
          </div>
    </section>
</template>

<script>
  export default {
    name: 'FooterMiddle',
    
    data(){
      return {

      }
    },

    methods: {

    },

    computed: {

    }
  }
</script>

<style lang="scss" scoped>
  @use '../../assets/style/partials/variables' as *;

  section
  {
    background-image: url('../../assets/img/footer-bg.jpg');
    background-size: cover;
    color: $white;
    overflow: hidden;
  }
  
  .container
  {
    position: relative;
    padding: 3rem 0;
    background-image: url('../../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: right;

  }
      
  a 
  {
    color: $footer-text;
    font-size: 0.8rem;
    display: block;
    padding: 2px 0;
    transition: 0.5s;

    &:hover
    {
      transition: 0.2s;
      color: $white;
    }
  }

  img
  {
    position: absolute;
    right: 0;
    top: 50%;
    transform: translate(0, -50%);
  }
    

</style>