<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

// implement
export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
}
</script>

<template>
    <AppHeader />
    <AppMain />
    <AppFooter />
</template>

<style lang="scss">
  @use './style/general.scss' as *;
  @use './style/partials/partials.scss' as *;
</style>
