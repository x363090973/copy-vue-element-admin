<template>
  <div class="home">
    <img
src="../assets/logo.png"
         alt="Vue logo">
    <HelloWorld :msg="opti" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  data: () => {
    return {
      opti: 'ssss'
    }
  }
}
</script>
