<script setup>
import AccordationView from './AccordationView.vue';
import { RouterLink } from 'vue-router';
import GalleryView from './GalleryView.vue';


</script>

<template>
    <div class="flex flex-col bg-[#000]">
      <div class="app-container flex justify-center relative mt-24 max-md:gap-6 max-xl:gap-12 gap-24 flex-wrap place-items-center">
        <div class="overlay-box2 max-md:order-2 lg:w-[40%] font-merriweather md:w-[50%] max-md:px-4 max-sm:w-[90%] max-vsm:w-[95%] w-[75%] mb-3">
          <h2 class="overlay-heading2 flex flex-col text-left text-[40px] pb-8 max-sm:pb-4 max-lg:pb-4 max-sm:text-[45px] max-ssm:text-[40px] max-vsm:text-[30px] max-vvsm:text-[30px]">
            <RouterLink to="/team" class="font-extrabold font-montserrat">The Group</RouterLink>
            <span class="text-[13px] tracking-wide ml-6 -mt-3 text-gray-300 relative font-thin font-merriweather">Click here to view team</span>
          </h2>
          <p class="mb-3 font-montserrat flex justify-center xxl:text[37px] text-[23px] max-sm:text-[23px] max-ssm:text-[21px] max-vsm:text-[21px] ">Team Natayaka is a vibrant and dynamic club dedicated to the art of dramatics. Comprising a diverse group of passionate individuals, we come together to celebrate the magic of storytelling through various theatrical forms. Our team members are not only talented actors but also skilled behind the scenes, including directors, producers, scriptwriters, and stage managers.</p>
          <span class="font-montserrat xxl:text[37px] text-[23px] max-sm:text-[23px] max-ssm:text-[21px] max-vsm:text-[21px] ">
            <span class="pr-2 font-bold font-montserrat xxl:text[41px] text-[27px] max-sm:text-[27px] max-ssm:text-[25px] max-vsm:text-[23px]">
              Judges:
            </span>
            <span class="font-semibold xxl:text[37px] text-[23px] max-sm:text-[23px] max-ssm:text-[21px] max-vsm:text-[21px]">
              B.Jaya Shankar 
            </span>
            <span class=" xxl:text[32px] text-[20px] max-sm:text-[20px] max-ssm:text-[18px] max-vsm:text-[16px] font-serif">
              (Nandi Award)
            </span> and
            <span class="font-semibold xxl:text[37px] text-[23px] max-sm:text-[23px] max-ssm:text-[21px] max-vsm:text-[21px]">Sk. Saida </span>
            <span class=" xxl:text[32px] text-[20px] max-sm:text-[20px] max-ssm:text-[18px] max-vsm:text-[16px] font-serif">(Senior Artist)</span>
            are the judges for Natayaka.
          </span>
        </div>
        <img class="md:w-[40%] max-md:order-1 max-ssm:w-[85%] w-[70%] saturate-0 bg-blend-color-burn" src="https://i.postimg.cc/VfqHdvWt/Team-Natayaka.jpg" alt="temp"/>
      </div>
      <div class="md:pt-24 pt-16">
        <GalleryView />
      </div>
      <div class="home-child"  id="partners-view">
        <!-- <PartnersView ref="homeChild" /> -->
      </div>
      <AccordationView />
    </div>
</template>