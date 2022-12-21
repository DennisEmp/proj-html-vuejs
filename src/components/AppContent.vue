<script>
</script>

<template>
    <div class="cont">
        <div class="txt">
            <h1>WORLD CLASS fitness</h1>
            <img src="../assets/img/divider-xx-red.png" alt="">
            <p id="text">At Avada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped to help you reach your goal of a healty and fit lifestyle.</p>
        </div>
    </div>
</template>

<style lang="scss">
    @use '../style/general.scss' as *;
    @use '../style/partials/partials.scss' as *;

    .cont {
        width: 100%;
        height: 400px;
        background-color: #252a2d;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .txt {
        color: #fff;
    }

    #text {
        width: 700px;
        margin-top: 10px;
    }
</style>