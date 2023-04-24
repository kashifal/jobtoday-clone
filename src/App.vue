<script setup lang="ts"> 
import Header from './components/HomePageComponents/Header.vue';
import HeroSection from './components/HomePageComponents/HeroSection.vue';
import SearchCity from './components/HomePageComponents/SearchCity.vue';
import PopularCity from './components/HomePageComponents/PopularCity.vue';
import Footer from './components/HomePageComponents/Footer.vue';
</script>

<template>
 <div id="__next">
  <Header />
  <!-- Hero Section for Desktop -->
  <HeroSection />
   <SearchCity />
   
  <div class="md:jt-container w-full md:mb-8 max-w-[1135px] mx-auto mt-28 ">
    <div class="bg-black p-4 pb-6 md:flex md:items-center md:justify-between md:rounded-3xl md:p-10">
      <div class="text-3xl font-black leading-[2.1rem] tracking-tight text-white">Are you <br class="md:hidden" />a business?</div>
      <div class="mt-16 md:mt-0"><a class="jt-btn-secondary-inverted-next jt-btn-md h-14 w-full text-lg" href="https://jobtoday.com/gb/landings/hire" data-testid="landing_busuness-hire-button">Post a job and hire</a></div>
    </div>
  </div>
  <div class="fixed bottom-0 z-10 flex w-full justify-center p-4 md:hidden max-w-[1135px] mx-auto">
    <div class="flex w-full min-w-[300px] max-w-[350px] shrink-0 flex-row items-center justify-between gap-2 rounded-[28px] bg-black p-4 pr-5">
      <img src="https://jobtoday.b-cdn.net/static/icons/ic-arrow-right-circle-gray-32.svg" alt="Download icon" height="32" width="32" /><button type="button" title="JOB TODAY iOS Application" data-testid="landing_appstore-button"><img src="https://jobtoday.b-cdn.net/static/images/appstore.svg" alt="App Store" width="116" height="54" /></button><button type="button" title="JOB TODAY Android Application" data-testid="landing_playstore-button"><img src="https://jobtoday.b-cdn.net/static/images/googleplay.svg" alt="Google Play" width="134" height="54" /></button>
    </div>
  </div>
 <!-- Popular Cities -->
   <PopularCity />
   <Footer />
</div>

</template>
 