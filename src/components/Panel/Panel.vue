<template>
  <div class="panel">
    <div class="title">
      {{title}}
    </div>
    <Card/>
    <Card/>
  </div>

</template>

<script>
import Card from "@/components/Panel/Card/Card";
export default {
  name: "Panel.vue",
  components: {Card},
  props: ["title"],
}
</script>

<style scoped>
  .panel{
    background-color: #f4f6f8;
    padding: 15px;
    text-transform: uppercase;
    font-size: 10pt;
    font-weight: bold;
    color: #7a7b81;
    border-radius: 3px;
    margin: 10px;
  }
  .title{
    display: block;
    margin-bottom: 20px;
  }
</style>