<template>
  <svg
    v-bind="$attrs"
    :width="size"
    :height="size"
    xmlns="http://www.w3.org/2000/svg"
    class="ui-svg-inline"
    viewBox="0 0 24 24"
    fill="currentColor"
  >
    <path
      d="M20.9,11.1c-0.4-0.2-4-2.3-4-2.3l0,0L4.6,1.7C4.4,1.5,4,1.5,3.7,1.6c0,0,0,0,0,0c0,0-0.1,0-0.1,0.1C3.2,1.8,3,2.2,3,2.6v19c0,0.3,0.2,0.7,0.4,0.8c0,0,0.1,0,0.1,0c0,0,0,0,0,0c0.1,0,0.2,0.1,0.3,0.1c0.2,0,0.4-0.1,0.6-0.2c0.4-0.2,12.4-7.2,12.4-7.2l4-2.3c0.4-0.2,0.6-0.5,0.6-0.9C21.5,11.6,21.3,11.2,20.9,11.1z M15.8,9.3l-2,2L6.4,3.8L15.8,9.3z M4,21L4,2.9l9.2,9.1L4,21z M6.4,20l7.4-7.4l2,1.9C14.2,15.6,9.4,18.3,6.4,20z M20.4,12l-3.7,2.1L14.6,12l2.2-2.1C17.6,10.3,19.8,11.6,20.4,12L20.4,12z"
    />
  </svg>
</template>

<script>
import '../utils/style.css'

export default {
  props: {
    size: {
      type: String,
      default: '1em'
    }
  }
}
</script>