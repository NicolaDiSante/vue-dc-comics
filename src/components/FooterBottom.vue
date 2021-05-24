<template>
  <footer>
  

      <div class="left-col">
         <button>SIGN-UP NOW!</button>
      </div>
      
      <div class="right-col">
        <ul>
          <li><a href="#">FOLLOW US</a></li>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""> </a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
        </ul>
      </div>

  
  </footer>
</template>

<script>
export default {
  name: 'FooterBottom'
}
</script>

<style lang="scss" scoped>

@import '@/assets/style/utilities.scss';
@import '@/assets/style/vars.scss';

footer{
  height: 100px;
  background-color: rgb(46, 46, 46);
  width: 100%;
  padding: 0 10%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  button{
    padding: 20px;
    background-color: rgb(46, 46, 46);
    border: 3px solid $brand-color;
    color: white;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
  }
  .right-col ul{
    display: flex;
    align-items: center;
    li{
      margin-left: 20px;
      &:first-child{
        font-size: 18px;
        font-weight: 500;
        a:first-child{
          color: $brand-color
        }
      }
    }
  }
}

</style>