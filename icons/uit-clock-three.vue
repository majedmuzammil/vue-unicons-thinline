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
      d="M15.5,11.5h-3v-5C12.5,6.223877,12.276123,6,12,6s-0.5,0.223877-0.5,0.5V12c0,0.0001831,0,0.0003662,0,0.0005493C11.5001831,12.2765503,11.723999,12.5001831,12,12.5h3.5c0.276123,0,0.5-0.223877,0.5-0.5S15.776123,11.5,15.5,11.5z M12,2C6.4771729,2,2,6.4771729,2,12s4.4771729,10,10,10c5.5201416-0.0064697,9.9935303-4.4798584,10-10C22,6.4771729,17.5228271,2,12,2z M12,21c-4.9705811,0-9-4.0294189-9-9s4.0294189-9,9-9c4.9683228,0.0054321,8.9945679,4.0316772,9,9C21,16.9705811,16.9705811,21,12,21z"
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