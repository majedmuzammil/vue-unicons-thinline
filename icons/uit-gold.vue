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
      d="M7.5,11h9c0,0,0.1,0,0.1,0c0.3,0,0.5-0.3,0.4-0.6l-1-6C16,4.2,15.7,4,15.5,4h-7C8.3,4,8,4.2,8,4.4l-1,6c0,0,0,0.1,0,0.1C7,10.8,7.2,11,7.5,11z M8.9,5h6.2l0.8,5H8.1L8.9,5z M22,13.4c0-0.2-0.2-0.4-0.5-0.4h-7c-0.2,0-0.5,0.2-0.5,0.4l-1,6c0,0,0,0.1,0,0.1c0,0.3,0.2,0.5,0.5,0.5h9c0,0,0.1,0,0.1,0c0.3,0,0.5-0.3,0.4-0.6L22,13.4z M14.1,19l0.8-5h6.2l0.8,5H14.1z M9.5,13h-7C2.3,13,2,13.2,2,13.4l-1,6c0,0,0,0.1,0,0.1C1,19.8,1.2,20,1.5,20h9c0,0,0.1,0,0.1,0c0.3,0,0.5-0.3,0.4-0.6l-1-6C10,13.2,9.7,13,9.5,13z M2.1,19l0.8-5h6.2l0.8,5H2.1z"
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