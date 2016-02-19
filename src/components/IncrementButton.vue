<template>
  <button @click.prevent="activate">+1</button>
</template>

<script>
  export default {
    methods: {
      activate () {
        // Send an event upwards to be picked up by App
        this.$dispatch('button-pressed')
      }
    }
  }
</script>