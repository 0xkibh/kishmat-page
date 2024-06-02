<template>
    <h2 class="text-xl font-semibold">Gallery</h2>
    <div class="flex flex-col ">
        <div class="flex flex-col md:flex-row mx-10 w-[90%] space-x-10">
            <NuxtImg class="image-k" src="/images/kishmat01.jpeg" alt="img1"/>
            <NuxtImg class="image-k" src="/images/kishmat_bhattarai.jpeg" alt="img2"/>
            <NuxtImg class="w-[350px]" src="/images/kishmat-03.jpg" alt="img4"/>
            <NuxtImg class="image-k" src="/images/kishmat.jpeg" alt="img3"/>
        </div>
    </div>
</template>

<style>
.image-k{
    height: 350px;
    object-fit: contain;
}
</style>