<template>
  <div id="app">
    <AdebiyiYinka :name="name" />
  </div>
</template>

<script>
import AdebiyiYinka from "./components/AdebiyiYinka.vue";

export default {
  name: "App",
  components: {
    AdebiyiYinka
  },
  data() {
    return {
      name: "Adebiyi Adeyinka Emmanuel"
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
