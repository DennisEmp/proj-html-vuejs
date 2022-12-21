<script>
import { store } from '../store'

export default {
  name: "AppHeader",
  data() {
        return {
            store,
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="navbar d-flex">
            <img src="/Users/dennis/Desktop/eserciziboolean/21dec/proj-html-vuejs/public/img/gym_logo_2x.png" alt="" srcset="">
            <ul>
                <li v-for="item in items" :key="item.text">
                    <a :href="item.href"> {{ item.text }} </a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style>

</style>