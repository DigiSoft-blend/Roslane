<script  setup>
  import navbar from '@/components/navbar.vue';
  import Banner from '@/components/Banner.vue';
  import Card from '@/components/Card.vue';
  import Card2 from '@/components/Card2.vue';
  import Card3 from '@/components/Card3.vue';
</script>

<template>
    <main>
        <div class="grid gap-4 sm:grid-cols-1 sticky top-0 z-0">
            <div class="bg-slate-100 col-span-full">
                <navbar/>
            </div>
        </div>
        <div class="grid gap-4 sm:grid-cols-1">
            <div class=" row-span-12  col-span-full">
                <Banner/>
                <hr class="mx-auto bg-black dark:bg-white">
            </div>
        </div>
        <div class="grid gap-2 m-6 sm:grid-cols-3">
            <div class="grid justify-center">
                <Card/>
            </div>
            <div class="grid justify-center">
                <Card2/>
            </div>
            <div class="grid justify-center">
                <Card3/>
            </div>
        </div>
    </main>
</template>

