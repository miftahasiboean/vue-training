<template>
  <div id="app">
    <MainHome />
    <router-view></router-view>
  </div>
</template>

<script>
import MainHome from './components/MainHome.vue'
export default {
  name: "App",
  components: {
    MainHome,
  }
}
</script>