<template>
  <div class='w-11/12 mx-auto'>
          <form >
              <input type="email" placeholder="Email or username" class="py-3 px-2 placeholder-gray-500 rounded-lg bg-gray-900 outline-none text-gray-300 focus:bg-gray-700 w-full">

              <div class="relative my-3">
                  <input type="password" placeholder='Password' class="py-3 px-2 placeholder-gray-500 rounded-lg bg-gray-900 outline-none text-gray-300 focus:bg-gray-700 w-full">
                  <div class='w-11 h-11 flex justify-center items-center rounded-full absolute right-2 top-0'>
                      <ion-icon name="eye-outline" v-if="false" class="w-9 text-xl text-gray-100 font-bold cursor-pointer"></ion-icon>
                      <ion-icon name="eye-off-outline" class="w-9 text-xl text-gray-100 font-bold cursor-pointer"></ion-icon>
                  </div>
              </div>

              <div>
                  <button class="w-full py-3 focus:outline-none text-center bg-blue-600 text-gray-200 rounded-lg">
                      Log in
                  </button>
              </div>

          </form>
          <div class='text-gray-400 text-center text-xs mt-20'>
              <p class="cursor-pointer inline  hover:text-blue-600" >
                  Forgot password?
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