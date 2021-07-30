<template>
  <div class="box">
    <View/>
    <div class="grid">
      <Profile/>
      <Message/>
    </div>

  </div>

</template>

<script>
import View from "@/components/Panel/Card/Action/View";
import Message from "@/components/Panel/Card/Action/Message";
import Profile from "@/components/Panel/Card/Action/Profile";
export default {
  name: "Action.vue",
  components:{
    View,
    Message,
    Profile
  }
}
</script>

<style scoped>
  .box{
    display: grid;
    grid-template-columns: auto auto;
    gap: 10px;
    max-width: 100%;
    align-items: center;
    background: white;
    margin-top: 1px;
    padding: 3px;
    border-radius: 0 0 7px 7px;
  }
  .grid>div{
    float: right;
  }
</style>