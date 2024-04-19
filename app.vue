<template>
  <NuxtPage />
</template>
<script setup lang="ts">
useHead({
  link: [ {href: "https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap", rel: "stylesheet"}]
})
</script>

<style lang="scss"> 
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html, body {
  height: 100%;
  width: 100%;
  font-family: 'Luckiest Guy';
}
body {
  background-image: url(~/assets/src/confetti-doodles.png);
  background-size: cover;
  background-position: top;
  > div#__nuxt {
    width: 100%;
    height: 100%;
  }
}
</style>