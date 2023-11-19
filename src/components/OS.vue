<template>
    <div class="containerOS">
        <div class="OS">
                    <div class="OSBtn" id="windows">
                        <img src="../assets/windows.png" alt="">
                        Windows
                    </div>
                    <div class="OSBtn" id="android">
                        <img src="../assets/android.png" alt="">
                        Android
                    </div>
                    <div class="OSBtn" id="ios">
                        <img src="../assets/ios.png" alt="">
                        iOS
                    </div>
                </div>
    </div>
</template>
   
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
    name: 'OS',
    props: {
        
    },
    components: {

    }
});
</script>
   
   
<style scoped>
.containerOS{
    display: flex;
    justify-content: center;
    width: max-content;
    
}
.OS {
    width: 100%;
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
    margin-left: 50px;
}
#android{
    margin-left: 50px;
}
</style>
   