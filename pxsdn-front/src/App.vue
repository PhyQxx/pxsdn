<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return{
      isRouterAlive: true,
    }
  },
  methods: {

  }
}
</script>

<style>
</style>
