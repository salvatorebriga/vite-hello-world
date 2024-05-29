<script>
  export default {
    name: "AppHero",
    data() {
      return {
        Text: "Sono il JumboTron!",
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
    width: 100%;
    padding-top: 150px;
    padding-bottom: 150px;
    background-color: aquamarine;
  }
</style>
