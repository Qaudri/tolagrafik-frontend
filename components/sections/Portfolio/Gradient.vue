<template>
  <div>
    <div class="gradient-bg flex justify-center items-center " >

      <button class="flex pt-4 cursor-pointer" @click="emitClickEvent">
        <p class="font-medium text-2xl text-white mx-4">See More</p>
        <img :src=" require('@/assets/images/expand_arrow.svg') " alt="" width="25px">
      </button>

    </div>
  </div>
</template>

<script>
export default {

    methods: {
      emitClickEvent(){
        this.$emit("btnClicked")
      }
    }

}
</script>

<style>
.gradient-bg{
  background: linear-gradient(transparent, black);
  background-size: 20vh;
  min-height: 10vh;
}
</style>