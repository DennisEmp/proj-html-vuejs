<script>
import { def } from "@vue/shared";
import AppContent from "./AppContent.vue";
import AppSignUp from "./AppSignUp.vue"
import AppInfo from "./AppInfo.vue"
import AppReview from "./AppReview.vue"
import AppPicture from "./AppPicture.vue"

export default {
    name: "AppMain",
    components : {
        AppContent,
        AppSignUp,
        AppInfo,
        AppReview,
        AppPicture
    }
}
</script>

<template>
  <AppContent />
  <AppSignUp />
  <AppInfo />
  <AppReview />
  <AppPicture />
</template>

<style>

</style>