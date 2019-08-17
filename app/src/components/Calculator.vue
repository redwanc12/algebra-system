<template>
  <div class="calculator">

    <div class="display">___</div>
    <div class="btn">Factor</div>
    <div class="btn">Solve for x</div>
    <div class="btn">÷</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">Clear</div>
    <div class="btn">9</div>
    <div class="btn">x</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn">+</div>
    <div class="btn zero">0</div>
    <div class="btn">.</div>
    <div class="btn">=</div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.calculator{
  font-size: 40px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
.display{
  grid-column: 1 / 5;
}
.zero{
  grid-column: 1 / 3;
}
.btn {
  background-color: #eee;
  border: 1px solid #333
}

</style>
