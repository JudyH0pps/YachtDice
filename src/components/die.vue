<template>
  <div class="die">
    <div class="reddot"></div>
    <div class="dot"></div>
  </div>
</template>

<script>


export default {
  name: 'die',
  components: {
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.die {
  display: flex;
  width: 50px;
  height: 50px;
  align-content: center;
}
.reddot{
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: red;
}
.dot{
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: black;
}
</style>
