<template>
  <img class=" transform sm:transform-gpu md:transform-none skew-y-12 p-6 m-10 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4" alt="Vue logo" src="./assets/logo.png">
  <HelloWorld class="p-6 text-center shadow-md center flex-shrink-0 mx-auto"  msg="Vue3 + Tailwind"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

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
