<template>
  <div class="card-body">
    <Menu/>
    <div class="display">
      <Image/>
      <div class="information">
        <Status/>
        <CountDown/>
        <div class="grid">
          <Price/>
          <Timer/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Image from "@/components/Panel/Card/Display/Image";
import Status from "@/components/Panel/Card/Display/Status";
import CountDown from "@/components/Panel/Card/Display/CountDown";
import Timer from "@/components/Panel/Card/Display/Timer";
import Price from "@/components/Panel/Card/Display/Price";
import Menu from "@/components/Panel/Card/Menu";
export default {
  name: "Display.vue",
  components: {Menu,Image,Status,CountDown,Timer,Price}
}
</script>

<style scoped>
.card-body{
  border-radius: 7px 7px 0 0;
  background: white;
  padding: 20px;
  padding-top: 10px;
}
.display{
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  max-width: 100%;
  align-items: center;
  margin-bottom: 1px;

}
.information{
  grid-column: 2/4;
  text-align: right;
}
.grid > div{
  float: right;
}
</style>