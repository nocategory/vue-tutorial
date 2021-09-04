<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <button type="button" @click="count++">count is: {{ count }}</button>
  <p v-if="count >= 5"><b>Wohooo! I'm bigger than 5</b></p>
</template>
