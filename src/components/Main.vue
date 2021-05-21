<template>

  <main>

    <div class="container-80">
      <h1> --> Content goes here &lt;-- </h1>
    </div>
    

  </main>
  

</template>

<script>
export default {
  name: 'Main'

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