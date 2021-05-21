<template>

  <footer>
    <div class="footer-con container-80">

      <div class="left-col">
        <div class="first-left-col">
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div>
          <h3>DC</h3>
          <ul>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshop</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div>
          <h3>SITES</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>

      </div>

      <div class="right-col">
        
      </div>
    </div>
  </footer>
  
</template>

<script>
export default {
  name: 'FooterTop'

}
</script>

<style lang="scss" scoped>

@import '@/assets/style/utilities.scss';

footer{
  height: 350px;
  width: 100%;
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  .footer-con{
    .left-col{
      float: left;
      display: flex;
      justify-content: space-around;
      padding: 20px 0;
      .first-left-col li:last-child{
        margin-bottom: 10px;
      }
      h3{
        color: white;
        margin-bottom: 10px;
      }
      ul{
        margin-right: 100px;
      }
      a{
        color: gray;
        font-size: 10px;
      }
    }
    .right-col{
      float: right;
      background-image: url("../assets/img/dc-logo-bg.png");
      background-position: 38px -100px;
      background-repeat: no-repeat;
      width: 600px;
      height: 350px;
  }
  }
  
  
}

</style>