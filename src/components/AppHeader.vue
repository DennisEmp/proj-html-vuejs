<script>

export default {
  name: "AppHeader",
  data() {
    return {
        items: [
        { text: 'HOME', href: '/home' },
        { text: 'ABOUT US', href: '/about' },
        { text: 'FACILITIES', href: '/facilities' },
        { text: 'MEMBERSHIP', href: '/member' },
        { text: 'TESTIMONIALS', href: '/testimonials' },
        { text: 'BLOG', href: '/blog' },
      ]
    }
  },
}
</script>



<template>
    <div class="navbar-top">
        <img class="logo" src="../assets/img/gym_logo_2x.png" alt="">
        <ul>
            <li v-for="item in items" :key="item.text">
                <a :href="item.href"> {{ item.text }} </a>
            </li>
        </ul>
    </div>
</template>




<style lang="scss" scoped>

.logo {
    width: 230px;
}

.navbar-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 1400px;
    text-align: center;
    background-color: grey;
}

ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

li {
  margin: 0 10px;
}

a {
  color: rgba(255, 255, 255, 0.761);
  text-decoration: none;
}
</style>