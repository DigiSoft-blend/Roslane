<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main >
    <div class="bg-white">
      <TheWelcome />
    </div>
    <section class="p-6 my-12 ">
   <h2 class="text-4xl font-bold text-center sm:text-5xl mb-6 text-slate-900 dark:text-white ">
    Our Music
   </h2>
 </section>

 <hr class="mx-auto bg-black dark:bg-white">

 <section class="p-6 my-12 ">
  <div class="max-w-sm rounded overflow-hidden shadow-lg">
  <img class="w-full" src="/src/assets/messaging-fun-concept-illustration.png" alt="Sunset in the mountains">
  <div class="px-6 py-4">
    <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
    <p class="text-gray-700 text-base">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
    </p>
  </div>
  <div class="px-6 pt-4 pb-2">
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
  </div>
</div>
 </section>

   

 <hr class="mx-auto bg-black dark:bg-white">

 <section class="p-6 my-12 ">
   <h2 class="text-4xl font-bold text-center sm:text-5xl mb-6 text-slate-900 dark:text-black ">
    Get Started 
   </h2>  
 </section>
  </main>
</template>
