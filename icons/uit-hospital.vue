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
      d="M12.5,17h-1c-0.3,0-0.5,0.2-0.5,0.5s0.2,0.5,0.5,0.5h1c0.3,0,0.5-0.2,0.5-0.5S12.8,17,12.5,17z M7.5,13h-1C6.2,13,6,13.2,6,13.5S6.2,14,6.5,14h1C7.8,14,8,13.8,8,13.5S7.8,13,7.5,13z M12.5,13h-1c-0.3,0-0.5,0.2-0.5,0.5s0.2,0.5,0.5,0.5h1c0.3,0,0.5-0.2,0.5-0.5S12.8,13,12.5,13z M7.5,17h-1C6.2,17,6,17.2,6,17.5S6.2,18,6.5,18h1C7.8,18,8,17.8,8,17.5S7.8,17,7.5,17z M13.5,7.5h-1v-1C12.5,6.2,12.3,6,12,6s-0.5,0.2-0.5,0.5v1h-1C10.2,7.5,10,7.7,10,8s0.2,0.5,0.5,0.5h1v1c0,0.3,0.2,0.5,0.5,0.5h0c0.3,0,0.5-0.2,0.5-0.5v-1h1C13.8,8.5,14,8.3,14,8S13.8,7.5,13.5,7.5z M21.5,7H18V2.5C18,2.2,17.8,2,17.5,2h-11C6.2,2,6,2.2,6,2.5V7H2.5C2.2,7,2,7.2,2,7.5v14C2,21.8,2.2,22,2.5,22h19c0.3,0,0.5-0.2,0.5-0.5v-14C22,7.2,21.8,7,21.5,7z M21,21H3V8h3.5C6.8,8,7,7.8,7,7.5V3h10v4.5C17,7.8,17.2,8,17.5,8H21V21z M17.5,17h-1c-0.3,0-0.5,0.2-0.5,0.5s0.2,0.5,0.5,0.5h1c0.3,0,0.5-0.2,0.5-0.5S17.8,17,17.5,17z M16.5,13c-0.3,0-0.5,0.2-0.5,0.5s0.2,0.5,0.5,0.5h1c0.3,0,0.5-0.2,0.5-0.5S17.8,13,17.5,13H16.5z"
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