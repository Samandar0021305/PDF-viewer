<template>
  <div id="app">
    <PdfViewer />
  </div>
</template>

<script>
import PdfViewer from "./components/PdfViewer.vue";

export default {
  name: "App",
  components: {
    PdfViewer,
  },
};
</script>
<style>
#app {
  width: 100%;
  height: 100vh;
}
</style>
