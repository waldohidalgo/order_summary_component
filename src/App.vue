<script>
import Footer from "./components/Footer.vue";

export default {
  components: {
    Footer,
  },
};
</script>

<template>
  <main class="bg-paleBlue py-[72px] sm:py-[101px] relative">
    <img
      src="./assets/pattern-background-mobile.svg"
      alt="background"
      class="w-full absolute top-0 left-0 z-[1] sm:hidden"
    />

    <img
      src="./assets/pattern-background-desktop.svg"
      alt="background"
      class="w-full absolute top-0 left-0 bottom-1/2 z-[1] hidden sm:block"
    />
    <div
      class="w-[86%] relative z-[2] mx-auto overflow-hidden rounded-[20px] shadow-darkBlue/10 shadow-[0px_36px_25px_0px] max-w-[450px]"
    >
      <img
        src="./assets/illustration-hero.svg"
        alt="Happy Music"
        class="w-full aspect-[450/220]"
      />
      <div
        class="flex flex-col items-center pt-[30px] pb-[33px] px-[23px] sm:px-[48px] bg-white sm:pt-[44px] sm:pb-[46px]"
      >
        <h2 class="text-[22px] font-black text-darkBlue sm:text-[28px]">
          Order Summary
        </h2>
        <p
          class="text-center mt-4 text-[15px] leading-[25px] text-desaturatedBlue font-semibold px-[9px] sm:mt-[14px] sm:px-[4px] sm:text-[16px] sm:leading-[27px]"
        >
          You can now listen to millions of songs, audiobooks, and podcasts on
          any device anywhere you like!
        </p>
        <div
          class="flex items-center self-stretch bg-paleBlue/40 rounded-[15px] p-4 mt-6 sm:mt-[20px] sm:p-[20px_22px]"
        >
          <img
            src="./assets/icon-music.svg"
            alt="music"
            class="w-[48px] aspect-square"
          />
          <div class="ms-[19px] md:ms-[21px]">
            <div class="font-black text-darkBlue text-[14px] sm:text-[16.3px]">
              Annual Plan
            </div>
            <div
              class="text-desaturatedBlue font-semibold text-[14.5px] sm:text-[17px] sm:mt-[3px]"
            >
              $59.99/year
            </div>
          </div>
          <a
            href="#"
            class="ml-auto text-brightBlue underline font-bold text-[13px] hover:text-brightBlue/70 sm:me-[5px] focus:text-brightBlue/70"
            >Change</a
          >
        </div>
        <button
          class="w-full bg-brightBlue shadow-darkBlue/20 shadow-[0px_18px_17px_0px] text-white rounded-[10px] py-[13px] mt-[23px] font-bold text-[15.4px] hover:bg-brightBlue/70 sm:mt-[35px] focus:bg-brightBlue/70"
        >
          Proceed to Payment
        </button>
        <a
          href="#"
          class="w-fit text-center font-black text-[15px] mt-[23px] text-desaturatedBlue hover:text-brightBlue sm:mt-[31px] focus:text-brightBlue"
          >Cancel Order</a
        >
      </div>
    </div>
  </main>
  <Footer />
</template>
