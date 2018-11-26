<template>
  <div class="users">
    <h1>This is Users</h1>
    <hello-world v-bind:msg="message"></hello-world>
  </div>
</template>
<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'product',
  components: {
    HelloWorld
  },
  data(){
      return {
        message:'Hi Users'
      }
  }
}
</script>