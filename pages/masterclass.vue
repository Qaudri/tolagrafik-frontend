<template>
  <div  >

    <SectionsCommonHeader />

    <div class="lg:flex mx-10 justify-center items-center pb-6">

      <div class="lg:w-1/2 pr-6" >
        <img :src=" require('@/assets/images/masterclass.jpg') " alt="">
      </div>

      <div class="lg:w-1/2">
        <p class="text-white text-base font-normal my-2">
          Creating lasting and functional identities for brands takes time. More time if you 
          begin without direction. One tip I have used over the years is to always sketch. In 
          fact, sketch fast and rough. You will get more ideas out. I will be sharing my over 
          10 years experience of creating identities with few people. Practical lessons on how 
          to create logos from scratch.
        </p>

        <div>
          <div class="text-white text-lg font-semibold my-2">
            What to expect:
          </div>

          <div class="grid list-grid">
            <ul class="text-white text-sm  font-normal list-disc px-3">

              <li class="max-w-1/2 my-1">
                Crash course on what is a logo
              </li>

              <li class="max-w-1/2 my-1">
                Understanding the different types of logos
              </li>

              <li class="max-w-1/2 my-1">
                Step by step guide to create a logo
              </li>

              <li class="max-w-1/2 my-1">
                Choosing a colour for your logo (Colour theory explained)
              </li>

            </ul>

            <ul class="text-white text-sm  font-normal list-disc px-3" >

              <li class="max-w-1/2 my-1">
                Creating a brand style guide
              </li>

              <li class="max-w-1/2 my-1">
                Resources: fonts, mock up, questionnaires, creative documents, etc.
              </li>

            </ul>

          </div>

          <div class="grid-container2">
            <div>
              <div class="text-white text-lg font-semibold my-2">
                Bonus:
              </div>

              <ul class="text-white text-sm font-normal list-disc px-3">
                <li class="my-1">
                  1 year mentorship
                </li>

                <li class="my-1">
                  Free hacks on how to monetize your skill
                </li>

                <li class="my-1">
                  Certificate after the class
                </li>

              </ul>
            </div>

            <div class="px-3">
              <div class="text-white text-lg font-semibold my-2">
                Price:
              </div>

              <p class="text-white text-sm  font-normal list-disc">
                Regular = ₦100,000
              </p>

              <p class="text-white text-sm  font-normal list-disc">
                Classes will hold on Whatsapp and Google Meet.
              </p>
            </div>

            <div>

            </div>
          </div>

          <div>
            <div>

              <div class="text-white text-lg font-semibold mt-2">
                How to Get Started:
              </div>

              <p class="text-white text-sm font-normal">
                Make payment to:
              </p>

              <div class="flex my-4">
                <img :src=" require('@/assets/images/gtb.jpg') " alt="" width="70px" />

                <div class="ml-4">
                  <p class="text-white text-base font-normal">Guaranty Trust Bank</p>
                  <p class="text-white text-base font-semibold ">0159520214</p>
                  <p class="text-white text-base font-normal">Busari Omotola Adeyinka</p>
                </div>
              </div>

              <p class="text-white text-base font-normal">Send Proof of payment to 08130071880</p>

            </div>
          </div>

        </div>

      </div>
    </div>

  </div>
</template>

<script>
export default {

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
  margin-bottom: .65em !important;
}

.list-grid{
  grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
  width: 100%;
}

.grid-container2{
  width: 100%;
  display: grid;
  -webkit-box-align: center;
  align-items: center;
  grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
}

</style>