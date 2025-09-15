<script setup>
import { defineProps } from "vue";

defineProps({
  cssClass: {
    type: String,
    default: "bg-gray-100 p-6 rounded-lg shadow-m",
  },
});
</script>

<template>
  <div :class="cssClass">
    <slot></slot>
  </div>
</template>
