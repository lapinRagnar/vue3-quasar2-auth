<template>
  <router-view />
</template>

<script setup>

import { authenticateRoutes } from '@vueauth/quasar-ui-auth'
authenticateRoutes()

// import { defineComponent } from 'vue'

// export default defineComponent({
//   name: 'App'
// })
</script>
