<script>
import { def } from "@vue/shared";
import AppContent from "./AppContent.vue";
import AppSignUp from "./AppSignUp.vue"
import AppInfo from "./AppInfo.vue"
import AppReview from "./AppReview.vue"
import AppPicture from "./AppPicture.vue"
import AppPng from "./AppPng.vue"
import AppTrainers from "./AppTrainers.vue"
import AppAchieve from "./AppAchieve.vue"

export default {
    name: "AppMain",
    components : {
        AppContent,
        AppSignUp,
        AppInfo,
        AppReview,
        AppPicture,
        AppPng,
        AppTrainers,
        AppAchieve
    }
}
</script>

<template>
  <AppContent />
  <AppSignUp />
  <AppInfo />
  <AppReview />
  <AppPicture />
  <AppPng />
  <AppTrainers />
  <AppAchieve />
</template>

<style>

</style>