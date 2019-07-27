<template>
  <div class="about">
   <HelloWorld hello="ようこそ"/>
    <h1>This is an about page</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  }
}
</script>