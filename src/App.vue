<template>
  <div>
    <Inner>
      <Item />
    </Inner>
  </div>
</template>
<script>
import Inner from './Inner.vue'
import Item from './Item.vue'
export default {
  components: {
    Inner,
    Item
  }
}
</script>