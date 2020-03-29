<template>
  <div id="app">
    <img alt="Sandeep App" src="./assets/shahi.jpg">
    <p>Post Component Should start here </p>
    <PostComponent />
        <p>Post Component should end here </p>

  </div>
</template>

<script>
import PostComponent from './components/PostComponent.vue'

export default {
  name: 'App',
  components: {
    PostComponent
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
