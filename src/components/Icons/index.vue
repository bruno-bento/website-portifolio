<template lang="">
    <component :is='name' v-bind="$props" />
</template>
<script>
import ArrowLeft from './ArrowLeft.vue'
import ArrowRight from './ArrowRight.vue'

export default {
  components: {
    ArrowLeft,
    ArrowRight
  },
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>