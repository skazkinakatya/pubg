<template>
    <div class="container">
        <div class="functional">
            <div class="funcLeft">
                <div class="OS">
                    <OS/>
                </div>
                <div class="phone">
                    <img src="../assets/Group808.png" alt="" id="phone">
                </div>
                <div class="arrows">
                    <img src="../assets/thin_big_right-1.png" alt="" id="arrowLeft">
                    <img src="../assets/thin_big_rightBlue.png" alt="" id="arrowRight">
                </div>
            </div>
            <div class="funcRight">
                <div class="title">
                    <div class="rect"></div>
                    <p class="titleH1">ФУНКЦИОНАЛ</p>
                    <div class="rect2"></div>
                    <span class="titleH2">
                        Уникальный чит на iOS подойдет для всех устройств <br>
                        начиная от айфона 4S+.
                    </span>
                </div>
                <div class="cheats">
                    <div class="cheat">
                        <img src="../assets/Rectangle1984.png" alt="">
                        <p class="cheatsNames">
                            <span class="name">WallHack</span>
                            - обнаруживает противников сквозь стены.
                        </p>
                    </div>
                    <div class="cheat">
                        <img src="../assets/Rectangle1984.png" alt="">
                        <p class="cheatsNames">
                            <span class="name">AntiRecoil</span>
                            - отключает отдачу на любом оружие.
                        </p>
                    </div>
                    <div class="cheat">
                        <img src="../assets/Rectangle1984.png" alt="">
                        <p class="cheatsNames">
                            <span class="name">Aimbot</span>
                            - автоматически наводит прицел на противника.
                        </p>
                    </div>
                    <div class="cheat">
                        <img src="../assets/Rectangle1984.png" alt="">
                        <p class="cheatsNames">
                            <span class="name">Drop</span>
                            - показывает топовые вещи сквозь стены.
                        </p>
                    </div>

                </div>
                <div class="warning">
                    <img src="../assets/warning.png" alt="">
                    <span>
                        Рекомендуем, оставить стандартные параметры в чите
                    </span>
                </div>
                <div class="btns">
                    <button class="buyBtn">
                        Купить
                        <img src="../assets/thin_big_right.png" alt="">
                    </button>
                    <button class="watchBtn">
                        Посмотреть видео
                        <img src="../assets/play.png" alt="">
                    </button>
                </div>

            </div>
        </div>


    </div>
</template>
   
<script lang="ts">
import { defineComponent } from 'vue';
import OS from './OS.vue';


export default defineComponent({
    name: 'functional',
    props: {

    },
    components:{
        OS
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
    position: relative;
}

.functional {
    display: flex;
    align-items: center;
    width: 75%;


}

.funcLeft {
    width: 50%;
    height: max-content;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.funcRight {
    width: 50%;
    height: max-content;
    display: flex;
    flex-direction: column;
    align-items: center;

}

.OS {
    width: 80%;
    display: flex;
    justify-content: space-between;
}

.OSBtn {
    width: max-content;
    padding: 2%;
    width: 200px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    height: 73px;
    background-color: white;
    color: #AAAAAA;
    border-radius: 5px;
}

#ios {
    background: linear-gradient(82.58deg,
            rgba(10, 166, 254, 1) 0%,
            rgba(5, 255, 255, 1) 100%);
    border-radius: 5px;
    width: 135px;
    height: 73px;
    position: relative;
    box-shadow: 0px 15px 25px 0px rgba(0, 163, 255, 0.3);
    color: white;
}

#phone {
    margin-left: -7%;
    margin-top: 5%;
}

.arrows {
    width: 30%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 2%;
}

.title {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.titleH1 {
    color: #2E3A59;
    font-family: Montserrat;
    font-size: 45px;
    font-style: normal;
    font-weight: 800;
    line-height: normal;
    margin-bottom: 3%;
}

.titleH2 {
    color: #828282;
    text-align: center;
    font-family: Montserrat;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    margin-top: 1%;

}

.cheats {
    width: 80%;
    margin-top: 5%;
}

.cheat {
    width: 100%;
    display: flex;
    align-items: center;
    margin-top: 1%;
}

.cheat img {
    margin-right: 1%;
}

.name {
    font-weight: 700;
    color: #2E3A59;
}

.cheatsNames {
    color: #2E3A59;
    font-weight: 500;
}

.warning {
    width: 649px;
    height: 87px;
    flex-shrink: 0;
    border-radius: 5px;
    background: #FFF;
    box-shadow: 0px 15px 25px 0px rgba(0, 0, 0, 0.199);
    color: #828282;
    font-weight: 400;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    margin-top: 5%;
}

.buyBtn {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background: linear-gradient(98.89deg,
            rgba(255, 155, 5, 1) 0%,
            rgba(255, 143, 63, 1) 100%);
    border-radius: 5px;
    width: 198px;
    height: 78px;
    position: relative;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.08);
    border: none;
    font-family: Montserrat;
    font-size: 18px;
    color: white;
}

.watchBtn {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background-color: #FF3B3B;
    border-radius: 5px;
    box-shadow: 0px 20px 35px 0px rgba(0, 0, 0, 0.08);
    width: 288px;
    height: 78px;
    font-family: Montserrat;
    font-size: 18px;
    color: white;
    border: none;
}

.btns {
    margin-top: 7%;
    width: 75%;
    display: flex;
    justify-content: space-between;
}

.rect {
    width: 40.225px;
    height: 8.045px;
    transform: rotate(-45deg);
    flex-shrink: 0;
    background: var(--primary02, #FB8500);
    position: relative;
    top: 55px;
    right: 190px;
    z-index: 101;
}
.rect2 {
    width: 40.225px;
    height: 8.045px;
    transform: rotate(-45deg);
    flex-shrink: 0;
    background: var(--primary02, #FB8500);
    position: relative;
    bottom:  25px;
    left: 190px;
    z-index: 101;
}
</style>
   