<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container max-auto">
    <div>
      <img class="logo" src="./assets/chat.svg">
    </div>
    <h1 class="text-3xl font-bold underline">
      Hello ChatPage!
    </h1>
  </div>
</template>

<style scoped>
.logo {
  height: 4em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
