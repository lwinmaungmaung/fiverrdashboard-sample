<template>
  <File/>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import File from "./components/File.vue";

export default defineComponent({
  name: "App",
  components: {
    File,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
