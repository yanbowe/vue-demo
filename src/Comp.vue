<template>
  <div @click="add">{{ modelValue }}</div>
</template>

<script setup>
const modelValue = defineModel({ required: true });
function add() {
  modelValue.value += 1;
}
</script>
<style scoped></style>
