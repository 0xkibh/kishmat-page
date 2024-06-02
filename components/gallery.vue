<template>
    <h2 class="text-lg md:text-xl font-semibold">Gallery</h2>
    <div class="flex flex-col">
        <div class="flex flex-col md:flex-row mx-1 md:mx-10 space-y-4 w-[90%] md:space-x-4 md:space-y-0">
            <div class="flex flex-col">
                <NuxtImg class="w-full md:h-[350px] md:object-contain" src="/images/kishmat01.jpeg" alt="img1"/>
                <p>Captured at: April 2024</p>
            </div>
            <div>
                <NuxtImg class="w-full md:h-[350px] md:object-contain" src="/images/kishmat_bhattarai.jpeg" alt="img2"/>
                <p>Captured at: Jan 2024</p>
            </div>
            <div>
                <NuxtImg class="w-full md:w-[350px]" src="/images/kishmat-03.jpg" alt="img4"/>
                <p>Captured at: June 2020</p>
            </div>
            <div>
                <NuxtImg class="w-full md:h-[350px] md:object-contain" src="/images/kishmat.jpeg" alt="img3"/>
                <p>Captured at: May 2019</p>
            </div>
        </div>
    </div>
</template>

<style>
.image-k{
    height: 350px;
    object-fit: contain;
}
</style>