<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <h2>dev上面的内容</h2>
    <h2>dev上面的内容</h2>
    <h2>dev上面的内容</h2>
    <h2>dev上面的内容</h2>
    <h2>dev上面的内容</h2>
    <h2>这是home组件</h2>
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
