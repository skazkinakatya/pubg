<template>
    <div class="container">
        <div class="aboutUs">
            <img src="../assets/Component4.png" alt="" id="stripes">
            <p>ЧТО ГОВОРЯТ О НАС</p>
        </div>

        <div class="squareLeft">
            <img src="../assets/right.png" alt="" id="arrowLeft">
        </div>
        <div class="squareRight">
            <img src="../assets/right.png" alt="" id="arrowRight">
        </div>

        <div class="reviewContainer">
            <div class="avatar">
                <img src="../assets/Rectangle2021.png" alt="">
            </div>
            <div class="reviewText">
                <p class="name">
                    Егор Черняев
                </p>
                <p class="review">
                    Рекомендую данный софт! Аналогов не нашел нигде, я решил не
                    заморачиваться и сразу приобрел ПРО версию и
                    теперь играю в свое удовольствие.
                </p>
            </div>
        </div>
    </div>
</template>
   
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
    name: 'Reviews',
    props: {

    },
    components: {

    }
});
</script>
   
   
<style scoped>
.container {
    margin-top: -4%;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    height: 620px;
    position: relative;
    background-image: url(../assets/Component3.png);
}

.aboutUs {
    margin-top: 11%;
    color: #FFF;
    font-family: Montserrat;
    font-size: 45px;
    font-style: normal;
    font-weight: 800;
    line-height: normal;
}

.reviewContainer {
    width: 826px;
    height: 220px;
    flex-shrink: 0;
    border-radius: 5px;
    background: #FFF;
    display: flex;
    flex-direction: column;
    align-items: center;
    color: #2E3A59;
    margin-top: 1%;
}

.avatar {
    margin-top: -5%;
}

.reviewText {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 65%;
}

.name {
    font-weight: 600;
}

.review {
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-align: center;
    margin-top: -1%;
}
.squareLeft,.squareRight{
    width: 115px;
    height: 115px;
    flex-shrink: 0;
    border-radius: 15px;
    position: absolute;
    background: linear-gradient(103deg, #0AA6FE -49.1%, #05FFFF 177.15%);
    box-shadow: 0px 0px 25px 0px rgba(0, 50, 180, 0.30) inset, 0px 4px 25px 0px rgba(10, 166, 254, 0.48);
} 
.squareLeft {
    transform: rotate(135deg);
    top: 69%;
    left: 25%;
}

.squareRight {
    transform: rotate(-45deg);   
    top: 69%;
    left:69%;
}
#arrowLeft, #arrowRight{
    position: relative;
    left: 45%;
    top: 35%;
    transform: rotate(45deg);
}
#stripes{
    position: absolute;
    top: 39%;
    left: 35%;
}

</style>
   