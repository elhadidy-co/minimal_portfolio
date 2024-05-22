<script setup>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';


</script>

<template>
  <TheHeader />
  <main>
    <RouterView />
  </main>
  <TheFooter />
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Reddit+Mono:wght@200..900&display=swap');

h1 {
  font-family: "Quicksand", sans-serif;
}

h3,
p {
  font-family: "Reddit Mono", monospace;
}
</style>