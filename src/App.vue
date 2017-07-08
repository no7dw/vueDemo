<template>
  <div id="app">
  {{ message }}
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      message: 'AWelcome to Your App'
    }
  }
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 260px;
}
</style>
