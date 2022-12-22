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
    <header>
        <div class="bg">
            <div class="navbar-top">
                <img class="logo" src="../assets/img/gym_logo_2x.png" alt="">
                <ul>
                    <li v-for="item in items" :key="item.text">
                        <a :href="item.href"> {{ item.text }} </a>
                    </li>
                </ul>
            </div>
            <div class="txt-header">
                <h1>NO PAIN NO GAIN</h1>
                <p>motivation is what gets you started. Habit is what keeps you going.</p>
                <button class="bttn">JOIN US TODAY</button>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>

.bg {
    background-image: url('../assets/img/home-banner.jpg');
    background-size: contain;
    height: 893px;
    display: flex;
    justify-content: center;
}
.logo {
    width: 230px;
}

.navbar-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    text-align: center;
    position: fixed;
    z-index: 999;
    padding: 65px;
    width: 100%;
}
.txt-header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    align-items: center;
    color: #fff;
}

.bttn {
    margin-top: 10px;
    width: 170px;
    background-color: transparent;
    border: #fff solid 1px;
    height: 40px;
    color: white;
    font-size: 12px;
}

h1 {
    font-size: 7.5rem;
}

p {
    font-size: 15px;
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