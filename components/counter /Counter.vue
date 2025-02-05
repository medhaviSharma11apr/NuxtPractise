

<script setup >
console.log('hi',);
const counter = userCounter();
</script>

<template>
  <div id="dummy_counter">
    Counter: {{ counter }}
    <button @click="counter++">
      +
    </button>
    <button @click="counter--">
      -
    </button>
  </div>
</template>