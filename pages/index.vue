<template>

  <div class="bg-black lg:min-h-screen lg:relative">
    <div>
    <div>
      <SectionsCommonHeader />
    </div>

    <div class="lg:flex lg:justify-between items-stretch ">
      <div class="lg:w-1/2 lg:absolute left-0 lg:bottom-0  lg:p-0 p-10 pb-0 pl-0">
        <img src="@/assets/images/tola-pic.png" alt="" width="100%" class="mt-14">
      </div>

      <div class="lg:px-16 lg:mb-2 flex lg:absolute md:py-4 md:px-10 px-8 py-6 lg:w-1/2 lg:right-0 lg:bottom-0 xl:mb-6">

        <!-- <div class="w-6/12"></div> -->
        <p class="font-normal text-white text-sm lg:text-base md:text-2xl md:leading-8 lg:leading-7 xl:text-xl xl:leading-10">
          
          Hi, I'm <span class="text-yellow-400">Omotola</span>!
            <br>
          My focus is to help businesses achieve desired visibility and growth, through the use of professional logo designs that resonates with their target audience.
            <br />
          With more than 500 satisfied clients across various sectors, your brand value matters and I am confident that you will find me resourceful as a designer to layout your ideas and keep you ahead of the game.
            <br />
          In clarity and simplicity paired with distinctive aesthetic, your brand is positioned to benefit from innovative solutions that I bring to bare.
            <br />
          I express a high level of professionalism, knowing that the right visual communications will no doubt lead to profitable growth, selling the right messages to the right people and at all times.
            <br />
          I enjoy working with start-ups, SMEs and businesses of all sizes. It gives me great pleasure to be part of your success stories.
            <br />
          Let's get ahead together!
            <br />
          Thank you.
        </p>
      </div>
    </div>

    <div>
      <UiSharedSocial />
    </div>
  </div>
  </div>

</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Manrope&family=Poppins:ital,wght@0,100;0,200;0,300;1,100;1,200;1,800&display=swap');

body{
  font-family: 'Manrope', sans-serif ;
}

br{   
  content: "A" !important;
  display: block !important;
  margin-bottom: .75em !important;
}
</style>
