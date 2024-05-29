<script>
  export default {
    name: "AppTitle",
    data() {
      return {
        Text: "La mia prima app con Vite!",
      };
    },
  };
</script>
<template>
  <div>
    <h1>{{ Text }}</h1>
  </div>
</template>
<style scoped>
  div {
    padding-top: 50px;
    padding-bottom: 50px;
  }
</style>
