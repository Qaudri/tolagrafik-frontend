<template>
  <div>

    <button 
      class="md:text-gray-500 text-white hover:text-yellow-300 xl:text-3xl font-normal text-2xl transition duration-1000 ease-in-out" @click="showOptions">
      Hire Me
    </button>

    <div class="px-4 py-2 absolute z-10 bg-black" :class=" options_showing ? 'block' : 'hidden' " >
      <div class="block">

        <a href="" 
          class="block md:text-gray-500 my-3 text-white hover:text-yellow-300 xl:text-3xl font-normal text-2xl transition duration-1000 ease-in-out">
          Whatsapp
        </a>

        <a href="" 
          class="block md:text-gray-500 my-3 text-white hover:text-yellow-300 xl:text-3xl font-normal text-2xl transition duration-1000 ease-in-out">
          Email
        </a>

      </div>

    </div>

  </div>
</template>

<script>
export default {

  data(){
    return{
      options_showing: false
    }
  },

  methods: {
    showOptions(){
      this.options_showing = true
    }
  }
}
</script>

<style>

</style>