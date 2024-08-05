<template>
    <div class="w-full bg-[#121212] text-white">
        <p class="font-bold text-xl py-2 mx-6 md:mx-24">CatPhotoApp</p>
    </div>
    <div class="bg-[url('assets/img/cat.jpeg')] h-[80vh] bg-cover bg-bottom">
        <div class="h-full flex flex-col justify-center md:justify-end  bg-black/50">
            <div class="md:mx-20 mx-4 p-4 my-4 text-white">
                <p class="text-6xl">All the Purr-fects Moments!</p>
                <button class="bg-white text-black px-4 py-2 mt-4 rounded text-xl w-full md:w-auto">See more
                    Photos</button>
            </div>
        </div>
    </div>
    <div class="mx-8 md:mx-24 space-y-4">
        <p class="font-bold text-2xl mt-4">Things cats love</p>
        <div class="flex md:flex-row flex-col justify-around space-y-4 ">
            <div class="flex flex-col items-center">
                <img class="w-48 rounded-full" src="/assets/img/catnip.png" alt="A slice of lasagna on a plate.">
                <p class="text-lg font-semibold">Catnip</p>
            </div>
            <div class="flex flex-col items-center">
                <img class="w-48 rounded-full" src="/assets/img/lasercat.png" alt="A slice of lasagna on a plate.">
                <p class="text-lg font-semibold">Laser Cat</p>
            </div>
            <div class="flex flex-col items-center">
                <img class="w-48 rounded-full" src="/assets/img/lasagna.jpeg" alt="A slice of lasagna on a plate.">
                <p class="text-lg font-semibold">Lasagna <span class="font-thin text-sm">(Yes, they love
                        Lasagna!)</span></p>
            </div>
        </div>
    </div>
    <div class=" bg-orange-200">
        <div class="mx-8 md:mx-24 py-2 space-y-4">
            <p class="font-bold text-2xl mt-4">Things cats hate</p>
            <div class="flex md:flex-row flex-col justify-around space-y-4 ">
                <div class="flex flex-col items-center">
                    <img class="w-48 rounded-full" src="/assets/img/wetcat.png" alt="A slice of lasagna on a plate.">
                    <p class="text-lg font-semibold">Water</p>
                </div>
                <div class="flex flex-col items-center">
                    <img class="w-48 rounded-full" src="/assets/img/lasercat.png" alt="A slice of lasagna on a plate.">
                    <p class="text-lg font-semibold">Thunder</p>
                </div>
                <div class="flex flex-col items-center">
                    <img class="w-48 rounded-full" src="/assets/img/cats.jpeg" alt="A slice of lasagna on a plate.">
                    <p class="text-lg font-semibold">Other Cats</p>
                </div>
            </div>
        </div>
    </div>
    <footer class="bg-[#121212] text-center py-4">
    <p class="text-sm text-white">&copy; 2024 Filhota. All rights reserved.</p>
  </footer>
</template>

<script setup lang="ts">

const loveThings = ref([
    { name: 'Lasagna', img: '/assets/img/lasagna.jpeg' },
    { name: 'Catnip', img: '/assets/img/catnip.png' },
    { name: 'laser', img: '/assets/img/lasercat.png' },
]);

</script>