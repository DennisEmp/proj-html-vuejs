<script>
</script>

<template>
    <div class="cont3">
        <div class="column">
            <div class="icon">
                <font-awesome-icon icon="fa-solid fa-link" />
            </div>
            <h5>Strength & Conditioning</h5>
            <img src="../assets/img/divider-x-red.png" alt="">
            <p id="txtinfo">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In augue nisl, ornare es volutpat etra us</p>
        </div>
        <div class="column">
            <div class="icon">
                <font-awesome-icon icon="fa-solid fa-bicycle" />
            </div>
            <h5>Strength & Conditioning</h5>
            <img src="../assets/img/divider-x-red.png" alt="">
            <p id="txtinfo">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In augue nisl, ornare es volutpat etra us</p>
        </div>
        <div class="column">
            <div class="icon">
                <font-awesome-icon icon="fa-solid fa-cloud" />
            </div>
            <h5>Strength & Conditioning</h5>
            <img src="../assets/img/divider-x-red.png" alt="">
            <p id="txtinfo">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In augue nisl, ornare es volutpat etra us</p>
        </div>
        <div class="column">
            <div class="icon">
                <font-awesome-icon icon="fa-solid fa-heart-pulse" />
            </div>
            <h5>Strength & Conditioning</h5>
            <img src="../assets/img/divider-x-red.png" alt="">
            <p id="txtinfo">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In augue nisl, ornare es volutpat etra us</p>
        </div>
    </div>
</template>

<style lang="scss">
    @use '../style/general.scss' as *;
    @use '../style/partials/partials.scss' as *;

    .cont3 {
        width: 100%;
        height: 600px;
        background-image: url("../assets/img/gym_bkgd_bw-compressor.jpg");
        background-position: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .column {
        color: #fff;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 360px;
        gap: 15px;
    }

    .icon {
        color: #d5625f;
        font-size: 40px;
        border: #d5625f solid 1px;
        border-radius: 50%;
        padding: 20px;
    }

    #txtinfo {
        font-weight: 100;
        font-size: 14px;
        width: 260px;
    }
</style>