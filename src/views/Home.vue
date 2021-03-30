<template>
  <div class="h-screen relative overflow-x-hidden home">
    <nav class='mx-5 flex justify-between items-center py-5 z-50'>
      <div class="w-4/12">
        <img :src="require('@/assets/logo_white.svg')" alt="">
      </div>
      <div class="w-4/12 flex justify-between items-center">
        <div><ion-icon name="add-circle-outline" class="w-9 mr-3 text-4xl text-gray-100 font-bold cursor-pointer"></ion-icon></div>
        <div><ion-icon name="heart-outline" class="w-9 mr-3 text-4xl text-gray-100 font-bold cursor-pointer"></ion-icon></div>
        <div><ion-icon name="paper-plane-outline" class="w-9 mr-3 text-4xl text-gray-100 font-bold cursor-pointer"></ion-icon></div>
      </div>
    </nav>

    <div class="relative">

        <div class="flex overflow-x-auto stories">
          
          <Story v-for="i in 13" :key='i' />
        </div>
        
        <section  class="pt-2">
          <Post v-for="i in 6" :key='i' />
        </section>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Post from '@/components/Post.vue'
import Story from '@/components/Story.vue'
export default {
  name: 'Home',
  components: {
    Post,Story
  }
}
</script>

<style >
  .story{
    min-width: 3.5rem;
  }
  .stories::-webkit-scrollbar{
    width:0
  }

  .home::-webkit-scrollbar{
    width: 0px
  }
</style>
