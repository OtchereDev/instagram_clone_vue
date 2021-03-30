<template>
  <div class="py-20 pb-10 min-h-screen relative ">
      <div class="w-6/12 mx-auto mt-5  mb-12">
          <img :src="require('@/assets/logo_white.svg')" class="w-full" alt="ig_logo">
      </div>
      <LogIn v-if="logging_in"/>
      <SignUp v-else />
      <div class='w-full py-4 absolute bottom-0 left-0 text-gray-400 text-center border-t border-gray-400 text-xs'>
          <p v-if="logging_in">
              Don't have an account? <span @click='logging_in=false' class="text-blue-600 cursor-pointer">Sign up.</span> 
          </p>
          <p v-else>
            Have an account? <span @click='logging_in=true' class="text-blue-600 cursor-pointer">Log in.</span> 
          </p>
      </div>
  </div>
</template>

<script>
import LogIn from '@/components/LogIn.vue'
import SignUp from '@/components/SignUp.vue'
import { ref } from '@vue/reactivity'
export default {
    components:{LogIn,SignUp},
    setup(){
        const logging_in = ref(true)

        return {logging_in}
    }

}
</script>

<style>

</style>