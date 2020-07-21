<template>
  <div class="board">
    <h1>Yacht Dice</h1>
    <score/>
    <gameboard/>
  </div>
</template>

<script>
import score from './score.vue'
import gameboard from './gameboard.vue'

export default {
  name: 'board',
  components: {
    score,
    gameboard,
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.board {
  margin: 0 10vw 0 10vw;
}
</style>
