<template>
  <offer />
  <functional />
  <reviews/>
  <price/>
  <questions/>

</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Offer from './components/Offer.vue';
import Functional from './components/Functional.vue';
import Price from './components/Price.vue';
import Reviews from './components/Reviews.vue';
import Questions from './components/Questions.vue';
import Footer from './components/Footer.vue';
import Contacts from './components/Contacts.vue';
import OS from './components/OS.vue';

export default defineComponent({
  name: 'App',
  components: {
    Offer,
    Functional,
    Price,
    Reviews,
    Questions,
    Footer,
    Contacts,
    OS
  }
});
</script>

<style>

  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
  box-sizing: border-box;
  /* border: 1px solid white; */
}

body {
  color: white;
  padding: 0px auto;
  margin: 0px auto;
  background-color: #F5F9FF;
  font-family: Montserrat;
  font-size: 17px;
  font-weight: 700;
  line-height: 21px;
  letter-spacing: 0em;
  text-align: left; 
  overflow-x: hidden;
}
</style>
