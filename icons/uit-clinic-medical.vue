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
      d="M11.5,12v1.5H10c-0.3,0-0.5,0.2-0.5,0.5s0.2,0.5,0.5,0.5h1.5V16c0,0.3,0.2,0.5,0.5,0.5h0c0.3,0,0.5-0.2,0.5-0.5v-1.5H14c0.3,0,0.5-0.2,0.5-0.5s-0.2-0.5-0.5-0.5h-1.5V12c0-0.3-0.2-0.5-0.5-0.5S11.5,11.7,11.5,12z M21.8,10.6l-9.5-8.4c-0.2-0.2-0.5-0.2-0.7,0l-9.5,8.4c-0.2,0.2-0.2,0.5,0,0.7c0.2,0.2,0.5,0.2,0.7,0l1.2-1v11.2C4,21.8,4.2,22,4.5,22h15c0.3,0,0.5-0.2,0.5-0.5V10.3l1.2,1c0.1,0.1,0.2,0.1,0.3,0.1v0c0.1,0,0.3-0.1,0.4-0.2C22.1,11.1,22,10.7,21.8,10.6z M19,21H5V9.4l7-6.2l7,6.2V21z"
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