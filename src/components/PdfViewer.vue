<template>
  <PDF :src="pdfUrl" />
</template>
<script setup>
import PDF from "pdf-vue3";

const props = defineProps({
  pdfUrl: {
    type: String,
    required: true
  }
});
</script>
