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
      d="M21.5,2H2.4993896C2.2234497,2.0001831,1.9998169,2.223999,2,2.5v19.0005493C2.0001831,21.7765503,2.223999,22.0001831,2.5,22h19.0006104C21.7765503,21.9998169,22.0001831,21.776001,22,21.5V2.4993896C21.9998169,2.2234497,21.776001,1.9998169,21.5,2z M14.5,21H3V3h11.5V21z M21,21h-5.5V3H21V21z"
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