<template>
  <div>
    <img :src="card.thumb" alt="">
  </div>
  
</template>

<script>
export default {
  name: 'Card',
  props:{
    card: Object
  }

}
</script>

<style lang="scss">

</style>