<script setup>

import { ref } from 'vue'

const data_count = ref(0)


function increment() {
  data_count.value++
}

</script>

<template>

    <button @click="increment">
    {{ data_count }}
  </button>

  <!-- Conditional Rendering -->

  <div v-if="type === 'A'">
  A
</div>
<div v-else-if="type === 'B'">
  B
</div>
<div v-else-if="type === 'C'">
  C
</div>
<div v-else>
  Not A/B/C
</div>

</template>
