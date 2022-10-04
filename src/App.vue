<script setup lang="ts">
import { ref } from 'vue';

const message = ref('Hello, World');
defineExpose({ message });
</script>
<template>
  <div>
    <h1 class="text-slate-700">{{ message }}</h1>
  </div>
</template>
