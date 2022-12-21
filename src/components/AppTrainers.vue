<script>
</script>

<template>
    <div class="cont7">
        <h1 style="margin-bottom: 40px">MEET OUR TRAINERS</h1>
        <img src="../assets/img/divider-xx-red.png" alt="" style="margin-bottom: 60px
        ;">
        <div class="containercards">
            <div class="card">
                <img src="../assets/img/trainer1.jpg" alt="">
                <div class="txt">
                    <p style="font-weight: 700;">Ann Baker <br> Personal Trainer</p>
                    <p style="font-weight: 100; font-size: 14px; margin-top: 40px;">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quisquam doloribus totam facere adipisci modi. Sunt dignissimos consectetur</p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/img/trainer3.jpg" alt="">
                <div class="txt">
                    <p style="font-weight: 700;">Anne Warren <br> Personal Trainer</p>
                    <p style="font-weight: 100; font-size: 14px; margin-top: 40px;">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quisquam doloribus totam facere adipisci modi. Sunt dignissimos consectetur</p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/img/trainer4.jpg" alt="">
                <div class="txt">
                    <p style="font-weight: 700;">Peter Rice <br> Personal Trainer</p>
                    <p style="font-weight: 100; font-size: 14px; margin-top: 40px;">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quisquam doloribus totam facere adipisci modi. Sunt dignissimos consectetur</p>
                </div>
            </div>
        </div>
        <button class="bttn">VIEW ALL TRAINERS</button>
    </div>
</template>

<style lang="scss" scoped>
.cont7 {
    width: 100%;
    height: 1000px;
    background-color: #1f2123;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    color: #fff;
}

.containercards {
    width: 60%;
    height: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.card {
    height: 100%;
    width: 30%;
    background-color: #25292b;
}

.txt {
    padding: 30px;
}

.bttn {
    margin-top: 50px;
    width: 170px;
    background-color: transparent;
    border: #fff solid 1px;
    height: 40px;
    color: white;
    font-size: 12px;
}

</style>