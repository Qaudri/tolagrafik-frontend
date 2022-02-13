<template>

  <div class="px-8 py-6 md:py-4 md:px-10 items-center">
    <div class="block md:flex justify-between">

      <div class="flex justify-between">

        <UiSharedLogo />  

        <div>
          <UiButtonsClosebtn @click="this.toggleButtons" :class="menuState.open ? 'block' : 'hidden' "  class="md:hidden cursor-pointer" />
          <UiButtonsMenubtn @click="this.toggleMenu" :class="menuState.open ? 'hidden' : 'block' "  class="md:hidden absolute z-10 right-8" />
        </div>

      </div>

      <div>
        <UiSharedMenu :class="menuState.open ? 'block' : 'hidden'" 
        class="md:block flex items-center absolute w-full md:relative bg-gray-800 bg-opacity-90 h-screen md:bg-transparent top-0 left-0" />
      </div>
    </div>


  </div>


</template>

<script>
export default{
	data(){
    return{
      menuState: {
        open: false,
        closed: true
      }
    }
  },

  methods: {
    toggleMenu(){
      this.menuState.open = true
      this.menuState.closed = false
    },

    toggleButtons(){
      this.menuState.open = false
      this.menuState.closed = true
    }
  }
}


</script>

<style>
body {
  max-height: 1.5rem;
}
</style>
