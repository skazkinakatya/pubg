<template>
    <div class="container">

        <img src="../assets/Component2.png" alt="" id="sparkle">


        <div class="header">
            <div class="logo">
                logo
            </div>
            <div class="nav">
                <ul>
                    <li><a href="">Главная</a></li>
                    <li><a href="">Тарифы</a></li>
                    <li><a href="">Отзывы</a></li>
                    <li><a href="">FAQ</a></li>
                    <li><a href="">Контакты</a></li>
                    <li><a href="">Функционал</a></li>
                </ul>
            </div>
            <div class="options">
                <div class="select">
                    <div id="select">
                        <img src="../assets/flags/Russia.png" alt="" id="ruFlag">
                        RU
                        <img src="../assets/caret_down.png" alt="">
                    </div>
                </div>
                <div class="profile">
                    <button id="profileBtn"></button>
                </div>
            </div>
        </div>


        <div class="offer">


            <div class="offerText">
                <p class="offerName">
                    ЧИТЫ НА P <img src="../assets/Component1.png" alt="" id="polygon"> UBG <br> ЛУЧШИЕ НА РЫНКЕ <br> БЕЗ
                    БАНА!
                </p>
                <div class="stripeS"></div>
                <p class="offerOverview">
                    Лучшие сборки на рынке, проверенные опытом и временем, а также, оптимальное соотношение цены, надежности
                    и производительности
                </p>
                <span class="bestPrice">
                    Самая низкая цена за мегахеш
                </span>
                <div class="offerBtns">
                    <button class="activeBtn">
                        Купить
                        <img src="../assets/thin_big_right.png" alt="">
                    </button>
                    <button class="deActiveBtn">Посмотреть видео</button>
                </div>
            </div>


            <div class="offerImage">
                <img src="../assets/image310.png" alt="" id="car">
                <img src="../assets/image336.png" alt="" id="pubg">
            </div>
        </div>


    </div>
    <div class="stripe">
        <img src="../assets/Rectangle 187.png" alt="">
    </div>
</template>
   
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
    name: 'offer',
    props: {
        msg: String,
    },
    components: {

    }
});
</script>
   
   
<style scoped>

#sparkle{
    position: absolute;
    z-index: 1;
}
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    height: 820px;
    position: relative;
    /* filter: blur(3.5px); */
    background: linear-gradient(113.28deg,
            rgba(26, 71, 234, 1) 0%,
            rgba(130, 233, 255, 1) 100%);
}

.stripe {
    position: relative;
    top: -100px;
    overflow: hidden;
}

.header {
    width: 1440px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 1%;
    position: relative;
    z-index: 105;
}

.nav {
    width: max-content;

}

.nav ul {
    list-style: none;
}

.nav ul li {
    display: inline-block;
    margin: 5px 45px;
}

.nav ul li a {
    text-decoration: none;
    color: white;
}

.options {
    display: flex;
}

#select {
    background-color: rgba(255, 255, 255, 0.705);
    padding: 7%;
    color: black;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100px;
    height: 40px;
    border: none;
    border-radius: 5px;
    margin-left: -7%;
}

#ruFlag {
    width: 40px;
}

#profileBtn {
    background-color: #FF9B05;
    width: 50px;
    height: 40px;
    background-image: url(../assets/user.png);
    background-position: center;
    background-size: 30%;
    background-repeat: no-repeat;
    border: none;
    border-radius: 5px;
}

.offer {
    width: 1440px;
    margin-top: 1%;
    display: flex;
}

.offerText {
    width: 50%;
}

.offerName {
    color: #FFF;
    font-family: Montserrat;
    font-size: 55px;
    font-style: normal;
    font-weight: 800;
    line-height: normal;
}

#polygon {
    margin-left: -3%;
    margin-right: -2%;
}

.stripeS {
    background: linear-gradient(120.79deg,
            rgba(255, 172, 139, 1) 0%,
            rgba(255, 73, 0, 1) 100%);
    border-style: solid;
    border-color: transparent;
    border-width: 1px;
    width: 110px;
    height: 5px;
    position: relative;
    box-shadow: 0px 0px 15px 0px rgba(0, 117, 255, 1);
    margin-top: -4%;
    position: relative;
    z-index: 100;
}

.offerOverview {
    color: #FFF;
    font-family: Montserrat;
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    margin-top: 5%;
}

.bestPrice {
    margin-top: 6%;
}
.offerBtns{
    width: 75%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 5%;
}

.activeBtn {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background: linear-gradient(98.89deg,
            rgba(255, 155, 5, 1) 0%,
            rgba(255, 143, 63, 1) 100%);
    border-radius: 5px;
    width: 240px;
    height: 78px;
    position: relative;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.08);
    border: none;
    font-family: Montserrat;
    font-size: 18px;
    color: white;
}

.deActiveBtn {
    border-width: 1px;
    border-style: solid;
    border-image: linear-gradient(113.71deg,
            rgba(169, 234, 255, 1) 0%,
            rgba(108, 255, 255, 1) 100%);
    border-image-slice: 1;
    width: 257px;
    height: 78px;
    position: relative;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.08);
    background-color: transparent;
    font-family: Montserrat;
    font-size: 18px;
    color: white;
    border-radius: 5px;
}
#car{
    position: absolute;
    left: 43%;
    top: 10%;
    z-index: 100;
}
#pubg{
    position: absolute;
    z-index: 101;
    left: 7%;
    top: 78%;
}
</style>
   