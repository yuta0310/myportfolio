<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png"> --> --> -->
    <img class="rei" alt="rei" src="../assets/rei.png">
    <HelloWorld hello="ようこそ"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style>
.rei{
  width:50%;
}
</style>