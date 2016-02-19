<template>
  <button @click.prevent="activate">+1</button>
</template>

<script>
import store from '../store'

export default {
  data () {
    return {
      sharedState: store.state
    }
  },
  methods: {
    activate () {
      this.sharedState.counter += 1
    }
  }
}
</script>