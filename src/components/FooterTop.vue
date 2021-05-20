<template>

  <footer>
    <div class="footer-con container-80">

      <div class="left-col">
        <div>
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
          </ul>
        </div>
        <div></div>
        <div></div>

      </div>

      <div class="right-col">
        <img src="../assets/img/dc-logo-bg.png" alt="">
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
  height: 450px;
  width: 100%;
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  .footer-con{
    display:flex;
    justify-content: space-between;
    .right-col{
    position: relative;
    img{
      position: absolute;
      top: -50px;
      height: 550px;
      width: 550px;
    }
  }
  }
  
  
}

</style>