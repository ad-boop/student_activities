<template>
  <h1>Hello World</h1>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Checkout from './components/Checkout.vue'
import Lesson from './components/Lesson.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
