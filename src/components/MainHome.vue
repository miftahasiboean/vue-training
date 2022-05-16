<template>
  <div id="'MainHome">
    <div>
      <h1>selamat datang!</h1>
      <button>
         <router-link to="/listBooks"> press! </router-link>  
      </button>
      <router-view></router-view> 
    </div>
  </div>
</template>

<script>
export default {
  name: "MainHome",
};
</script>

<style>
</style>