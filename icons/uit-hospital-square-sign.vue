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
      d="M15.5,6C15.2,6,15,6.2,15,6.5v5H9v-5C9,6.2,8.8,6,8.5,6S8,6.2,8,6.5v11C8,17.8,8.2,18,8.5,18h0C8.8,18,9,17.8,9,17.5v-5h6v5c0,0.3,0.2,0.5,0.5,0.5h0c0.3,0,0.5-0.2,0.5-0.5v-11C16,6.2,15.8,6,15.5,6z M19.5,2h-15C3.1,2,2,3.1,2,4.5v15C2,20.9,3.1,22,4.5,22h15c1.4,0,2.5-1.1,2.5-2.5v-15C22,3.1,20.9,2,19.5,2z M21,19.5c0,0.8-0.7,1.5-1.5,1.5h-15C3.7,21,3,20.3,3,19.5v-15C3,3.7,3.7,3,4.5,3h15C20.3,3,21,3.7,21,4.5V19.5z"
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