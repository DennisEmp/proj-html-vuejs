<script>
</script>

<template>
    <div class="cont4">
        <div class="col-8 ">
            <h1 style="margin-bottom: 50px;">REAL WORLD RESULTS</h1>
            <img src="../assets/img/divider-xx-red.png" alt="" style="margin-bottom: 80px;">
                <div class="contcard">
                    <div class="singlecard">
                        <img src="../assets/img/review_1-compressor.jpg" alt="">
                        <div class="textcontainer">
                            <p>"The trainers of Avada Gym have helped me reach my fitness goals beyond anything I could of hoped for. I love it!"</p>
                            <p>-Tara Smith</p>
                        </div>
                    </div>
                    <div class="singlecard">
                        <img src="../assets/img/review_2-compressor.jpg" alt="">
                        <div class="textcontainer">
                            <p>"The atmosphere of Avada Gym is amazing, the peaple are even better. All in all, is a great place to work out."</p>
                            <p>-Simon Chel</p>
                        </div>
                    </div>
                    <div class="singlecard">
                        <img src="../assets/img/review_3-compressor-2.jpg" alt="">
                        <div class="textcontainer">
                            <p>"The facilities at Avada Gym stood out to me the most. They are well maintained and have high quality equipment."</p>
                            <p>-Jen Wirth</p>
                        </div>
                    </div>
                    <div class="singlecard">
                        <img src="../assets/img/review_4-compressor-2.jpg" alt="">
                        <div class="textcontainer">
                            <p>"No bad things to say about Avada Gym, the are top notch at every corner and truly take care of their costumers."</p>
                            <p>-Jeff Glum</p>
                        </div>
                    </div>
                </div>
        </div>
    </div>
</template>

<style lang="scss">
  @use '../style/general.scss' as *;
  @use '../style/partials/partials.scss' as *;

  .cont4 {
        width: 100%;
        height: 1200px;
        background-color: #252a2d;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .col-8 {
        color: #fff;
    }

    .contcard {
        width: 100%;
        height: 600px;
        display: flex;
        flex-wrap: wrap;
    }

    .singlecard {
        width: calc(50% - 20px);
        height: calc(50% - 20px);
        background-color: #1f2123;
        margin: 10px;
        display: flex;
        padding: 40px;
        gap: 20px;
    }

    .textcontainer {
        width: 60%;
        text-align: start;
        font-weight: 100;
        margin: auto;
        font-size: 15px;
        line-height: 30px;
    }
</style>