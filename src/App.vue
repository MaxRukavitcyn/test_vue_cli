<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
    </div>

    <router-view/>

  </div>
</template>
<script lang="ts">
  import Vue from "vue";

  export default Vue.extend({
    name: 'App',
    data(){
      return {
      }
    },

  })
</script>
<style>

</style>
