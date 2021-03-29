<template>
    <div>

        <div class="story cursor-pointer min-w h-14 rounded-full bg-indigo-50 mx-2 overflow-hidden " style="background: linear-gradient(45deg,#EBAF4D,#D60A66);padding:2px">
            <img :src="require('@/assets/pic-1.jpg')" class="w-full h-full rounded-full" alt="">
        </div>
        <p class="text-gray-200 text-xs mt-1">
            OtchereDev
        </p>
    </div>
    <div class="absolute max-h-full overflow-hidden h-full w-full z-10 left-0 top-0 bg-black bg-opacity-10 flex justify-center pt-20">
        <img :src="require('@/assets/pic-1.jpg')" class="max-w-full h-1/6 " style="width:98%" alt="">
    </div>
</template>

<script>
export default {

}
</script>

<style>
.story{
    min-width: 3.5rem;
  }
</style>