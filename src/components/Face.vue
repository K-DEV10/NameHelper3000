<script setup>
defineProps({
  surname: {
    type: String,
    required: true
  },
  IMGpath: {
    type: String,
    required: true
  },
}),
elon = "src/img/elon.png"
bezos="src/img/bezos.png"
jobs = "src/img/jobs.png"
zuckerberg = "src/img/zuckerberg.png"


  
</script>

<template>
  <div class="image">
    Pan/Paní: {{surname}}.
    <img v-bind:alt="surname" src = {{IMGpath}} />
  </div>
</template>

<style scoped>
</style>
