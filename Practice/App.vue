<script setup>
import { ref } from vue
const msg = ref('Hello world') 

</script>

<template>
    {{ msg }}
    <input v-model="msg">
</template>