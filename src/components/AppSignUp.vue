<script>
</script>

<template>
    <div class="cont2">

        <div class="col-4">
            <img src="../assets/img/home_img-compressor.jpg" alt="">
        </div>

        <div class="col-4 inputbox">
            <p id="white" >Sign Up For A Free Training Session!</p>

            <div class="mb-3">
                <label for="exampleFormControlInput1">Name</label>
                <input type="name" class="" id="exampleFormControlInput1" placeholder="">
            </div>

            <div class="mb-3">
                <label for="exampleFormControlTextarea1">Email</label>
                <input type="email" class="" id="exampleFormControlInput1" placeholder="">
            </div>
            <button id="buttonorange">START NOW!</button>
        </div>
    </div>
</template>

<style lang="scss">
    @use '../style/general.scss' as *;
    @use '../style/partials/partials.scss' as *;

    .cont2 {
        width: 100%;
        height: 600px;
        background-color: #070809;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    label {
        color: #fff;
        font-size: 12px;
        margin-bottom: 10px;
        font-weight: 100;
    }

    .inputbox {
        display: flex;
        flex-direction: column;
        align-items: start;
        gap: 10px;
    }

    .mb-3 {
        display: flex;
        flex-direction: column;
        align-items: start;
    }

    #white {
        font-size: 26px;
        color: #fff;
        font-weight: 300;
    }

    input {
        width: 470px;
        background-color: #070809;
        border: 1px solid #252a2d;
    }

    #buttonorange {
        width: 470px;
        height: 40px;
        font-weight: 100;
        text-align: center;
        text-decoration: none;
        background-color: #d5625f;
        color: #fff;
        border: none;
    }
</style>