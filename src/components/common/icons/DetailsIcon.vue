<template>
  <svg class="icon details-icon" width="16" height="16" viewBox="0 0 16 16">
    <path
      fill-rule="evenodd"
      clip-rule="evenodd"
      d="M8 7C7.44772 7 7 7.44772 7 8C7 8.55228 7.44772 9 8 9C8.55228 9 9 8.55228 9 8C9 7.44772 8.55228 7 8 7ZM6 8C6 6.89543 6.89543 6 8 6C9.10457 6 10 6.89543 10 8C10 9.10457 9.10457 10 8 10C6.89543 10 6 9.10457 6 8Z"
      :fill="color"
    />

    <path
      fill-rule="evenodd"
      clip-rule="evenodd"
      d="M3 7C2.44772 7 2 7.44772 2 8C2 8.55228 2.44772 9 3 9C3.55228 9 4 8.55228 4 8C4 7.44772 3.55228 7 3 7ZM1 8C1 6.89543 1.89543 6 3 6C4.10457 6 5 6.89543 5 8C5 9.10457 4.10457 10 3 10C1.89543 10 1 9.10457 1 8Z"
      :fill="color"
    />

    <path
      fill-rule="evenodd"
      clip-rule="evenodd"
      d="M13 7C12.4477 7 12 7.44772 12 8C12 8.55228 12.4477 9 13 9C13.5523 9 14 8.55228 14 8C14 7.44772 13.5523 7 13 7ZM11 8C11 6.89543 11.8954 6 13 6C14.1046 6 15 6.89543 15 8C15 9.10457 14.1046 10 13 10C11.8954 10 11 9.10457 11 8Z"
      :fill="color"
    />
  </svg>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import variables from '@/assets/variables'

export default defineComponent({
  name: 'DetailsIcon',
  props: {
    color: {
      type: String,
      default: variables.cGrey1000,
    },
  },
})
</script>
