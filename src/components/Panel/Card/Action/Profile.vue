<template>
  <div>
    <img src="@/assets/profile.jpg" alt="Profile">
  </div>
</template>

<script>
export default {
  name: "Profile",
  methods: {
    greet: function(event){
      alert('Hello World');
    }
  }
}
</script>

<style scoped>
  div{
    width: 35px;
    height: 35px;
    border-radius: 50%;
    overflow: hidden;
    align-content: center;
    margin-right: 15px;
  }
  img{
    max-width: 100%;
  }
</style>