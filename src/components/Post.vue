<template>
   <div class="my-2">
        <div class="flex justify-between items-center px-2">
          <div class='flex w-5/12 items-center'>
            <div class="w-14 h-14 bg-black rounded-full overflow-hidden flex justify-center items-center">
              <img :src="require('@/assets/profile.jpg')" alt="profile picture" class="w-full h-full">
            </div>
            <div class="text-gray-50 ml-4">
              <p>
                OtchereDev
              </p>
              <p>
                Accra, Ghana
              </p>
            </div>
          </div>
          <div class="w-1/12">

          </div>
        </div>
        <div class="w-full h-96 bg-black mt-1 flex justify-center items-center overflow-">
            <img :src="require('@/assets/pic-1.jpg')" class='max-w-full max-h-full ' alt="">
        </div>
        <div class="flex justify-between items-center p-2">
          <div class="flex w-4/12">
            <div class="mr-3 w-8"><ion-icon name="heart" class="w-9 mr-3 text-red-500 text-4xl font-bold cursor-pointer"></ion-icon></div>
            <div class="mr-3 w-8"><ion-icon name="chatbubble-outline" class="w-9 mr-3 text-4xl text-gray-100 font-bold cursor-pointer"></ion-icon></div>
            <div class="mr-3 w-8"><ion-icon name="paper-plane-outline" class="w-9 mr-3 text-4xl text-gray-100 font-bold cursor-pointer"></ion-icon></div>
          </div>
          <div class="flex items-center -ml-12">
            <div class="w-1 h-1 mr-1 rounded-full bg-blue-500"></div>
            <div class="w-1 h-1  rounded-full bg-gray-200"></div>
          </div>
          <div class="flex justify-center items-center w-1/12">

            <img :src="require('@/assets/tag_white.svg')" class="w-8/12" alt="">
          </div>
        </div>

        <div class="mx-2">
          <p class="text-white text-sm">
            <span class="font-medium  mr-2 ">
              OtchereDev
            </span>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          </p>
          <p class="text-blue-500 text-sm">
            #youtuber #best_dev #vuejs
          </p>
        </div>
      </div>
</template>

<script>
export default {

}
</script>

<style>

</style>