<script setup>
  import Amelia from '../components/Amelia.vue'
</script>

<style scoped>
.flex-container {
  display: flex;
  flex-wrap: wrap;
}
h1 {
  color: green;
  text-align: center;
}
@media only screen and (in-width: 600px) {
  main {
    background-color: white;
  }
}
</style>

<template>
  <Amelia/>
</template>

