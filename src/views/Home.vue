<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Button>按♣钮</Button>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import { Button } from 'ant-design-vue';
export default {
  name: 'Home',
  components: {
    HelloWorld,
    Button
  }
}
</script>
