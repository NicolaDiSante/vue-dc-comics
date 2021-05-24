<template>

  <main>
    
    <div class="container-80">
      <Cards 
        v-for="(card, index) in cards"
        :key="index"
        :card="card"
      />
    </div>
    

  </main>
  

</template>

<script>

import cards from "@/assets/data/dc-comics.js"
import Cards from "@/components/Cards"

export default {
  name: 'Main',
  components: {
    Cards
  },
  data(){
    return {
      cards
    }
  },
  mounted(){
    
  }

}
</script>

<style lang="scss" scoped>

@import '@/assets/style/utilities.scss';

main{
  display: flex;
  align-items: center;
  height: 100px;
  width: 100%;
  background-color: black;
  h1{
  color: white;
}
}


</style>