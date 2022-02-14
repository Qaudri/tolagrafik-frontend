<template>

  <div class="px-8 py-6 md:py-4 md:px-10 items-center header">
    <div class="block md:flex justify-between">

      <div class="flex justify-between">

        <UiSharedLogo />  

        <div>
          <!-- <UiButtonsClosebtn /> -->
          <img @click="toggleMenu" :class="is_menu_open ? 'block' : 'hidden' "  class="md:hidden cursor-pointer"  :src="require('@/assets/images/delete.svg')" alt="" width="35px" />
          <!-- <img  @click="toggleMenu" :class="is_menu_open ? 'hidden' : 'block' "  class="md:hidden absolute z-10 right-8" :src="require('@/assets/images/menu.svg')" alt="" width="35px" /> -->
          <UiButtonsMenubtn @menuClicked="toggleMenu" />
        </div>

      </div>

      <div>
        <UiSharedMenu :class="is_menu_open ? 'block' : 'hidden'" 
        class="md:block flex items-center absolute w-full md:relative bg-gray-800 bg-opacity-90 h-screen md:h-auto md:bg-transparent top-0 left-0" />
      </div>
    </div>


  </div>


</template>

<script>
export default{
	data(){
    return{
      is_menu_open: false,
    }
  },

  methods: {
    toggleMenu(){
      this.is_menu_open = !this.is_menu_open
    },

  }
}


</script>

<style>
.header {
  /* max-height: .2rem; */
  /* position: absolute;
  z-index: 99999; */
  width: 100%;
}
</style>
