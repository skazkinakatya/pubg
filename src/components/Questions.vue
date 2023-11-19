<template>
    <div class="container">


        <div class="rect"></div>
        <p class="h1">ЧАСТЫЕ ВОПРОСЫ</p>
        <div class="rect2"></div>


        <div class="answer">

        </div>
       

    </div>
</template>
   
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
    name: 'Questions',
    props: {
        
    },
    components: {

    }
});
</script>
   
   
<style scoped>
.container{
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 5%;
}
.h1{
    color: #2E3A59;
font-family: Montserrat;
font-size: 45px;
font-style: normal;
font-weight: 800;
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
    right: 250px;
    z-index: 101;
}
.rect2 {
    width: 40.225px;
    height: 8.045px;
    transform: rotate(-45deg);
    flex-shrink: 0;
    background: #0AA6FE;
    position: relative;
    bottom: 40px;
    left: 260px;
    z-index: 101;
}

</style>
   