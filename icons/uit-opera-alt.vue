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
      d="M12,5.5c-3.1,0-3.1,4.7-3.1,6.4c0,1.8,0,6.6,3.2,6.6c3.2,0,3.2-4.8,3.2-6.6C15.1,7.7,14.1,5.5,12,5.5z M12,17.5c-1.5,0-2.2-1.8-2.2-5.7c0-3.6,0.7-5.3,2.1-5.3h0c1.4,0,2.2,1.8,2.2,5.4C14.1,15.7,13.5,17.5,12,17.5z M12,1.5c-5.8,0-9.8,4.3-9.8,10.4c0,5.2,3.7,10.6,9.8,10.6c6.1,0,9.8-5.4,9.8-10.6C21.8,5.8,17.8,1.5,12,1.5z M12,21.5c-5.5,0-8.8-4.9-8.8-9.6c0-5.6,3.5-9.4,8.8-9.4c5.3,0,8.8,3.8,8.8,9.4C20.8,16.6,17.5,21.5,12,21.5z"
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