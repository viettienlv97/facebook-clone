<template>
  <app-header />
</template>

<script>
import Header from './components/HomeHeader.vue'

export default {
  name: 'App',
  components: {
    AppHeader: Header
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  height: 1000px;
}
</style>
