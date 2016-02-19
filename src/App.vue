<template>
  <div id="app">
    <h3>Increment:</h3>
    <increment></increment>
    <h3>Counter:</h3>
    <counter></counter>
  </div>
</template>

<script>
import Counter from './components/CounterDisplay.vue'
import Increment from './components/IncrementButton.vue'

export default {
  components: {
    Counter,
    Increment
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
