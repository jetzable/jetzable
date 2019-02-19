<template>
  <z-canvas :views='$options.components'></z-canvas>
</template>
<script>
import Home from './views/Home'
export default {
  components: {
    Home
  },
  mounted () {
    this.$zircle.setView('Home')
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700');
@import url('https://use.fontawesome.com/releases/v5.1.0/css/all.css');
</style>