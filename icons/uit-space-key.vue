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
      d="M21.5,9C21.223877,9,21,9.223877,21,9.5V14H3V9.5C3,9.223877,2.776123,9,2.5,9S2,9.223877,2,9.5v5c0,0.0001831,0,0.0003662,0,0.0005493C2.0001831,14.7765503,2.223999,15.0001831,2.5,15h19c0.0001831,0,0.0003662,0,0.0006104,0C21.7765503,14.9998169,22.0001831,14.776001,22,14.5v-5C22,9.223877,21.776123,9,21.5,9z"
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