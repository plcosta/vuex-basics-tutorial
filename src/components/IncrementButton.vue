<template>
  <button @click.prevent="activate">+1</button>
</template>

<script>
import store from '../store'

export default {
  methods: {
    activate () {
      store.dispatch('INCREMENT')
    }
  }
}
</script>