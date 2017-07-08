<template>
  <div id="app">
  <router-view></router-view>
  {{ message }}
  </div>
</template>

<script>
export default {
  name: 'app',
  message: 'Hey It'
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 260px;
}
</style>
