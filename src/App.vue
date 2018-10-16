<template>
  <div id="app">
      <div class="container text-center">
        <movies-app></movies-app>
      </div>
  
  </div>
</template>

<script>

  import MoviesApp from './components/MoviesApp.vue'

export default {
  name: 'app',
  components:{
    MoviesApp
  }
  
}
</script>

<style>

</style>
