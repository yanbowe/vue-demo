<script setup>
import { ref } from 'vue'
import Comp from './Comp.vue'

const count = ref(1)
</script>

<template>
  <Comp v-model="count"/>
</template>