<template>
  <div class="app">
    <h1>Vue Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from './main/Calculator.vue'
export default {
    components: { Calculator }
}
</script>

<style>
@font-face {
    font-family: "RobotoMono";
    src: url("./fonts/Roboto-Thin.ttf");
}
*{
    font-family: "RobotoMono", monospace;
}
body{
    margin: 0;
}
.app{
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    background: linear-gradient(to right, rgb(226, 190, 226),rgb(94, 3, 94));
}
</style>