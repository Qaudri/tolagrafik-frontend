<template>
  <div>

    <div>

      <SectionsCommonHeader />

    </div>

    <div class="relative">
      <div>
        <SectionsPortfolioGradient @btnClicked="revealMore" class="absolute w-full bottom-0" />
      </div>

      <div>
        <SectionsPortfolioPortfoliomain />

        <SectionsPortfolioSecond class="mt-3" :class="is_revealed ? 'block' : 'hidden' " />
      </div>



    </div>

  </div>

</template>

<script>
export default {
  data(){
    return{
      is_revealed: false
    }
  },
  methods: {

    revealMore(){
      this.is_revealed = true
    }
  }
}
</script>

<style >
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