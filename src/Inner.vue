<template>
  <Outer>
    <slot />
  </Outer>
</template>

<script>
import Outer from './Outer.vue'
export default {
  components: {
    Outer
  }
}
</script>

<style scoped>
:slotted(*) {
  color: blue
}
</style>