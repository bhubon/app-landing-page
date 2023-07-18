<script setup>
const imageUrl  = 'https://images.pexels.com/photos/16790135/pexels-photo-16790135/free-photo-of-fog-over-bare-trees-in-forest.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1';
const linkUrl  = 'https://google.com';
</script>

<template>

  <img :src="imageUrl" />
  <a :href="linkUrl">Click Me</a>

</template>

<style scoped>
</style>
