<script setup>
import Top from './components/Top.vue'
import Bottom from './components/Bottom.vue'
import HomeView from './components/views/HomeViews.vue'

</script>

<template>
  <div class="container">
    <Top />
    <HomeView />
    <Bottom />
  </div>
</template>

<style scoped>
.container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}

* {
  margin: 0;
  padding: 0;
  border: 0;
}
</style>