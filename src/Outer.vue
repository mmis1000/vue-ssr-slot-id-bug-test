<template>
  <div>
    <slot />
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
:slotted(*) {
  background: red
}
</style>