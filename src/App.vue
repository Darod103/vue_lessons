<script setup>
import { ref } from 'vue';
const text = ref('');
</script>
<template>
<input 
    type="text"
    placeholder="Add text"
    :value="text"
    @input="e => text = e.target.value">
<p>{{ text }}</p>
</template>

<style scoped>
</style>
