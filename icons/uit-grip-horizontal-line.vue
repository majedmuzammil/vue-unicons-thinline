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
      d="M2.5,11h19c0.276123,0,0.5-0.223877,0.5-0.5S21.776123,10,21.5,10h-19C2.223877,10,2,10.223877,2,10.5S2.223877,11,2.5,11z M21.5,14h-19C2.223877,14,2,14.223877,2,14.5S2.223877,15,2.5,15h19c0.276123,0,0.5-0.223877,0.5-0.5S21.776123,14,21.5,14z"
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