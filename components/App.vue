<template>
  <!-- eslint-disable-next-line -->
  <div class="container" v-html="author" />
</template>

<script lang="ts">
import { createComponent, ref } from '@vue/composition-api'

export default createComponent({
  setup() {
    const author = ref('&#8734;')

    return {
      author
    }
  }
})
</script>

<style>
.container {
  line-height: 100vh;
  text-align: center;
  font-size: 88px;
}
</style>
