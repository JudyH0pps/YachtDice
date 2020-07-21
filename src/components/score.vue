<template>
  <div class="paper">
    <table>
      <tr>
        <th class="black">Categories</th>
        <th>P1</th>
        <th>P2</th>
      </tr>
      <tr>
        <td>Ones</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Deuces</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Threes</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Fours</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Fives</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Sixes</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td class="black">Subtotal</td>
        <td class="gray"></td>
        <td class="gray"></td>
      </tr>
      <tr>
        <th class="black updot">+35 Bonus</th>
        <td class="gray updot"></td>
        <td class="gray updot"></td>
      </tr>
      <small>보너스</small>
      <tr>
        <td class="bottomlabel">Choice</td>
        <td></td>
        <td></td>
      </tr>
      <hr>
      <tr>
        <td class="bottomlabel">4 of a Kind</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td class="bottomlabel">Full House</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td class="bottomlabel">S. Straight</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td class="bottomlabel">L. Straight</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td class="bottomlabel">Yacht</td>
        <td></td>
        <td></td>
      </tr>
      <hr>
      <tr>
        <td class="black">Total</td>
        <td class="gray"></td>
        <td class="gray"></td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
    name: 'score',
    data: () => {
        return {

        }
    }
}

</script>

<style scoped>
.updot{
    border-top: 2px white dotted !important;
}
.paper{
    display:inline-block;
    background:#eeeeee;
}
table{
    margin: 15px 15px 15px 15px;
    border-collapse: collapse;
}
.black{
    background: #696969;
    border: 1px solid #696969;
    color: white;
}
.gray{
    background: gray;
    border: 1px solid #696969;
    color: white;
}
hr{
    border: none;
    margin: 2px;
    width: 0;
}
.bottomlabel{
    border-right: double;
}
tr,
th,
td{
    background: white;
    border: 1px solid black;
    padding: 5px;
}
tr{
    height: 30px;
}
th, td{
    width: 50px;
}
</style>