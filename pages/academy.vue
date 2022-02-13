<template>

  <div>

    <SectionsCommonHeader />

    <div class="md:flex">

      <div class="md:h-screen md:w-1/2">
        <img :src=" require('@/assets/images/academy.jpg') " alt="" width="100%" class="bg-no-repeat">
      </div>

      <div class="md:w-1/2">
        <SectionsAcademyGrid />
      </div>
    </div>

  </div>
  

</template>

<script>
export default {
  name: 'AcademyPage'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Manrope&family=Poppins:ital,wght@0,100;0,200;0,300;1,100;1,200;1,800&display=swap');

body{
  font-family: 'Manrope', sans-serif ;
  background: #000000;
}

br{   
  content: "A" !important;
  display: block !important;
  margin-bottom: .75em !important;
}
</style>
