<template lang="">
  <svg
    :width="size"
    :height="size"
    viewBox="0 0 18 32"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M2 2L16 16L2 30"
      :stroke="color"
      stroke-width="4"
      stroke-linecap="round"
      stroke-linejoin="round"
    />
  </svg>
</template>
<script>
export default {
  props: {
    size: {
      type: [String, Number],
      default: 22,
    },
    color: {
      type: String,
      default: "white",
    },
  },
};
</script>
