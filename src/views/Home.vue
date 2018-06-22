<template>
  <div class="home">
    <h1>REFACTORING.LIFE</h1>
    <h3>Changing my life and documenting it</h3>
    <h6>-Rudy Quevedo</h6>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    // HelloWorld
  }
}
</script>
<style lang="scss">
.home{
  height: 100vh;
  position: relative;
  h1, h3, h6{
    margin:0px;
  }
}
.coming-soon{
  position: fixed;
  bottom: 0px;
  height: 20px;
  width: 97%;
  background: #0E1E25;
  color: #c4c4c4;
  text-align: center;
  p{
    margin:0px;
  }
}
</style>
