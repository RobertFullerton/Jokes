<template>
  <div>
    <AppHeader />
    <Nuxt />
  </div>
</template>
<script>
import AppHeader from '~/components/AppHeader.vue'
export default {
  name: 'default-vue',
  components: {
    AppHeader
  }
}
</script>
