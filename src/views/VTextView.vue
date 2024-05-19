<script setup>
import { ref } from 'vue'

// 筆記：這裡的 ref 是 Vue 3 的 Composition API 的一部分
// 筆記：ref 是一個響應式函數，它接受一個參數，並返回一個具有 value 屬性的對象
// 筆記：v-text 顯示的是 ref 的 value 屬性
// TODO ...
const msg = ref('Hello VTextView')
</script>
<template>{{ msg }}</template>
<style scoped></style>
