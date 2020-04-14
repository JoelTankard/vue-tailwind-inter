<template>
  <div class="home flex justify-center items-center h-screen">
    <div class="text-center">
          <img class="inline-block w-32" alt="Vue logo" src="../assets/logo.png">
          <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
