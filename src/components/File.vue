<template>
  <div class="grid">
    <div class="item"><Panel title="New Orders"/></div>
    <div class="item"><Panel title="In Progress"/></div>
    <div class="item"><Panel title="Waiting for Buyers"/></div>
    <div class="item"><Panel title="Completed"/></div>
  </div>
</template>

<script>
import Panel from "@/components/Panel/Panel";
export default {
  name: "File.vue",
  components:{
    Panel
  }
}
</script>

<style scoped>
  .grid{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    grid-auto-columns: auto;
    max-width: 94%;
    margin: auto auto 0px auto;
  }
</style>