<template>
  <div>
    <div class="gradient-bg flex justify-center items-center">

      <div class="flex pt-4">
        <p class="font-medium text-2xl text-white mx-4">See More</p>
        <img :src=" require('@/assets/images/expand_arrow.svg') " alt="" width="25px">
      </div>

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.gradient-bg{
  background: linear-gradient(transparent, black);
  background-size: 20vh;
  min-height: 10vh;
}
</style>