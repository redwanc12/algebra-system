<template>
  <div class="calculator">

    <div class="display">0</div>
    <div class="btn top">AC</div>
    <div class="btn top">Factor</div>
    <div class="btn top">Solve</div>
    <div class="btn op">÷</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn op">x</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn op">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn op">+</div>
    <div class="btn zero">0</div>
    <div class="btn">.</div>
    <div class="btn op">=</div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.calculator{
  margin: 0 auto;
  width: 400px;
  font-size: 30px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
.display{
  grid-column: 1 / 5;
  background-color: #333;
  color: white;
}
.zero{
  grid-column: 1 / 3;
}
.btn {
  background-color: #777;
  color: white;
  border: 0.5px solid black;
}
.op {
  background-color: orange;
  color: white;
}
.top{
  background-color: #555;
}

</style>
