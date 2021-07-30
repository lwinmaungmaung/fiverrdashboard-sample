<template>
  <div class="card">
    <Display/>
    <Action/>
  </div>
</template>

<script>
import Display from "@/components/Panel/Card/Display/Display";
import Action from "@/components/Panel/Card/Action/Action";
export default {
  name: "Card.vue",
  components: {
    Action,
    Display,
  }
}
</script>

<style scoped>
  .card{
    max-width: 100%;
    box-shadow: 0 0 5px #DDD;
    background: #cccccc;
    border-radius: 7px;
    margin-bottom: 15px;
  }
</style>