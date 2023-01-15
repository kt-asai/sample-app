<template>
  <div>staging branch: {{ msg }}</div>
  <!-- <Tutorial /> -->
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  data() {
    return {
      msg: process.env.msg
    }
  }
})
</script>
