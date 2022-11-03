<template>
  <h1>App</h1>
  <HomePage />
</template>

<script>
import HomePage from './components/Home.vue'
export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
h1 {
  text-align: center;
}
</style>
