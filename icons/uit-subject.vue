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
      d="M2.5,8h19C21.776123,8,22,7.776123,22,7.5S21.776123,7,21.5,7h-19C2.223877,7,2,7.223877,2,7.5S2.223877,8,2.5,8z M13.5,17h-11C2.223877,17,2,17.223877,2,17.5S2.223877,18,2.5,18h11c0.276123,0,0.5-0.223877,0.5-0.5S13.776123,17,13.5,17z M21.5,12h-19C2.223877,12,2,12.223877,2,12.5S2.223877,13,2.5,13h19c0.276123,0,0.5-0.223877,0.5-0.5S21.776123,12,21.5,12z"
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