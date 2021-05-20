<template>
  
  <header class="container-80">

    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="DC Logo">
    </div>

    <div>
      <ul>
        <li v-for="(link, index) in links" :key="index">
          <a :class="{'active' : link.current}" :href="link.url"> {{ link.text }} </a>
        </li>
      </ul>
    </div>

  </header>

</template>

<script>
export default {
  name: 'Header',
  data(){
    return{
      links:[
        {
          text: 'Characters',
          url: '#',
          current: false
        },
        {
          text: 'Comics',
          url: '#',
          current: false
        },
        {
          text: 'Movies',
          url: '#',
          current: false
        },
        {
          text: 'Tv',
          url: '#',
          current: false
        },
        {
          text: 'Games',
          url: '#',
          current: false
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false
        },
        {
          text: 'Videos',
          url: '#',
          current: false
        },
        {
          text: 'Fans',
          url: '#',
          current: false
        },
        {
          text: 'News',
          url: '#',
          current: false
        },
        {
          text: 'Shop',
          url: '#',
          current: false
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

@import '@/assets/style/utilities';
@import '@/assets/style/vars.scss';

header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: white;
  padding: 10px 0;
  li{
    display: inline;
    text-transform: uppercase;
    margin-left: 15px;
    a{
      color: black;
      font-size: 13px;
      font-weight: 700;
      padding-bottom: 52px;
      &:hover,
      &.active{
        border-bottom: 3px solid $brand-color;
        color: $brand-color;
      }

    }
  }
}


</style>