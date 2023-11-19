<template>
    <div class="container">
        <div class="rect"></div>
        <h1>Тарифы</h1>
        <div class="rect2"></div>
        <OS class="OS" />
        <div class="priceBoxes">


            <div class="priceBox">

                <div class="priceName">
                    <p>ОБЫЧНАЯ</p>
                </div>
                <div class="priceText">

                    <p class="month">1 месяц</p>

                    <div class="services">


                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Весь функционал чита</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Обновления 1 раз в месяц</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Техническая поддержка</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Анти-Бан</span>
                        </div>
                        <div class="service">
                            <img src="../assets/close_big.png" alt="">
                            <span>Улучшенная оптимизация</span>
                        </div>
                        <div class="service">
                            <img src="../assets/close_big.png" alt="">
                            <span>Запуск на других телефонах</span>
                        </div>
                        <div class="service">
                            <img src="../assets/close_big.png" alt="">
                            <span>DPI+, ASN, SKK</span>
                        </div>




                    </div>
                    <p class="priceTag">649 <span class="rubles">₽</span></p>
                </div>
                <div class="priceBtn">
                    <div class="priceBtnText">
                        <span>Приобрести</span>
                        <img src="../assets/thin_big_right.png" alt="">
                    </div>

                </div>

            </div>


            <div class="priceBox">
                <div class="priceName" id="priceName2">
                    <p>Стандартная</p>
                </div>
                <div class="priceText">

                    <p class="month">3 месяца</p>

                    <div class="services">


                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Весь функционал чита</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Обновления 1 раз в месяц</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Техническая поддержка</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Анти-Бан</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Улучшенная оптимизация</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Запуск на других телефонах</span>
                        </div>
                        <div class="service">
                            <img src="../assets/close_big.png" alt="">
                            <span>DPI+, ASN, SKK</span>
                        </div>




                    </div>
                    <p class="priceTag">1499 <span class="rubles">₽</span></p>
                </div>
                <div class="priceBtn">
                    <div class="priceBtnText">
                        <span>Приобрести</span>
                        <img src="../assets/thin_big_right.png" alt="">
                    </div>

                </div>
            </div>
            <div class="priceBox" id="priceBox2">
                <div class="priceName" id="priceName3">
                    <p>PRO ВЕРСИЯ</p>
                </div>
                <div class="priceText">

                    <p class="month">Навсегда</p>

                    <div class="services">


                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Весь функционал чита</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Обновления 1 раз в месяц</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Техническая поддержка</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Анти-Бан</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Улучшенная оптимизация</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>Запуск на других телефонах</span>
                        </div>
                        <div class="service">
                            <img src="../assets/check.png" alt="">
                            <span>DPI+, ASN, SKK</span>
                        </div>

                    </div>
                    <p class="priceTag">2899 <span class="rubles">₽</span></p>
                </div>
                <div class="priceBtn">
                    <div class="priceBtnText">
                        <span>Приобрести</span>
                        <img src="../assets/thin_big_right.png" alt="">
                    </div>

                </div>
            </div>


        </div>
    </div>
</template>
   
<script lang="ts">
import { defineComponent } from 'vue';
import OS from './OS.vue';


export default defineComponent({
    name: 'Price',
    props: {

    },
    components: {
        OS
    }
});
</script>
   
   
<style scoped>
.container {
    width: 100%;
    margin-top: 3%;
    display: flex;
    flex-direction: column;
    align-items: center;
    color: #2e3a59;
}

h1 {
    font: 800 45px "Montserrat";
    text-transform: uppercase;
}

.OS {
    width: max-content;
}

.priceBoxes {
    width: 1440px;
    display: flex;
    justify-content: space-between;
    margin-top: 3%;
}


.priceBox {
    background: #ffffff;
    border-radius: 5px 55px 5px 55px;
    width: 416px;
    height: 666px;
    position: relative;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.05);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.priceName {
    background: linear-gradient(103.24deg,
            rgba(5, 255, 255, 1) 0%,
            rgba(10, 166, 254, 1) 100%);
    border-radius: 5px 55px 0px 55px;
    width: 416px;
    height: 71px;
    position: relative;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.05);
}

#priceName2 {
    border-radius: 5px 55px 0px 55px;
    background: linear-gradient(89deg, #DDA6FF -5.85%, #D828F4 106.28%);
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.05);
}

#priceName3 {
    border-radius: 5px 55px 0px 55px;
    background: linear-gradient(99deg, #FF9898 14.64%, #FF1F00 102.27%);
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.05);
}

.month {
    color: #2E3A59;
    text-align: center;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    font-family: Montserrat;
    font-size: 30px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.priceName {
    width: 100%;
    text-align: center;
    color: #FFF;
    font-family: Montserrat;
    font-size: 21px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    text-transform: uppercase;
}

.service span {
    color: #2E3A59;
    font-family: Montserrat;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    margin-left: 3%;
}

.services {
    width: 80%;

}

.priceText {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
}

.service {
    width: 100%;
    display: flex;
    align-items: center;
    padding-top: 3%;
    padding-bottom: 3%;
}


.priceBtn {
    background: linear-gradient(98.89deg,
            rgba(255, 155, 5, 1) 0%,
            rgba(255, 143, 63, 1) 100%);
    border-radius: 5px 0px 0px 55px;
    width: 416px;
    height: 76px;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.08);
    display: flex;
    align-items: center;
    justify-content: center;
}

.priceBtnText {
    width: 70%;
    color: #ffffff;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.priceTag {
    color: #2E3A59;
    font-family: Montserrat;
    font-size: 45px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}
.rect {
    width: 40.225px;
    height: 8.045px;
    transform: rotate(-45deg);
    flex-shrink: 0;
    background: var(--primary02, #FB8500);
    position: relative;
    top: 40px;
    right: 140px;
    z-index: 101;
}
.rect2 {
    width: 40.225px;
    height: 8.045px;
    transform: rotate(-45deg);
    flex-shrink: 0;
    background: var(--primary02, #FB8500);
    position: relative;
    bottom: 40px;
    left: 150px;
    z-index: 101;
}
.rubles{
    position: relative;
    top: -30%;
}
</style>
   