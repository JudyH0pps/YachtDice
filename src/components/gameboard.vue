<template>
  <div class="gameboard">
    <die></die>
    
  </div>
</template>

<script>
import die from './die.vue'

export default {
  name: 'gameboard',
  components: {
    die
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.gameboard{
  float: left;
  border-radius: 25px;
  border: 15px solid lavender;
  padding: 0;
  margin: 0 0 0 10vh;
  width: 65vh;
  height: 65vh;
}
</style>
