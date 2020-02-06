<template>
  <App />
</template>

<script lang="ts">
import { createComponent } from '@vue/composition-api'

// import Component: App
import App from '@/components/App.vue'

export default createComponent({
  components: {
    App
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
