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
<style>
  div {
    padding: 25px;
    text-align: center;
  }
</style>
