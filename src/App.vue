<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div id="app">
    <AppTitle />
    <p>Welcome to my Vite app</p>
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';

export default {
  components: {
    AppTitle
  }
};
</script>
