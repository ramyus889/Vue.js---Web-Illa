<script>
export default {
  name: 'UseMain',
  mounted() {
    document.title = 'illa dev';
  }
};
</script>
<template>
  <div class="flex place-content-center mt-[164px] px-5">
    <div class="flex flex-col gap-3">
      <div
        data-aos="fade-up"
        data-aos-delay="100"
        class="md:text-[80px] text-[40px] md:leading-[88px] leading-[40px] text-center font-bold"
      >
        Create business apps like assembling blocks
      </div>
      <div data-aos="fade-up" data-aos-delay="300" class="text-center font-semibold mt-3">
        Build
        <span class="bg-gradient-to-r from-[#1ED2D2] to-[#B1E6E6] text-transparent bg-clip-text"
          >website&app</span
        >
        with low code, make automated
        <span class="bg-gradient-to-r from-[#923DFF] to-[#AC8CD6] text-transparent bg-clip-text"
          >flow</span
        >, create
        <span class="bg-gradient-to-r from-[#E632A9] to-[#B87EA5] text-transparent bg-clip-text"
          >AI Agent</span
        >
        easily
      </div>
      <div class="flex place-content-center mt-[24px]">
        <button
          data-aos="fade-up"
          data-aos-delay="500"
          class="group group-hover:before:duration-500 group-hover:after:duration-500 after:duration-500 hover:border-rose-300 hover:before:[box-shadow:_20px_20px_20px_30px_#a21caf] duration-500 before:duration-500 hover:duration-500 underline underline-offset-2 hover:after:-right-8 hover:before:right-12 hover:before:-bottom-8 hover:before:blur hover:underline hover:underline-offset-4 origin-left hover:decoration-2 hover:text-rose-300 relative bg-neutral-800 h-16 w-64 border text-left p-3 text-gray-50 text-base font-bold rounded-full overflow-hidden before:absolute before:w-12 before:h-12 before:content[''] before:right-1 before:top-1 before:z-10 before:bg-violet-500 before:rounded-full before:blur-lg after:absolute after:z-10 after:w-20 after:h-20 after:content[''] after:bg-rose-300 after:right-8 after:top-3 after:rounded-full after:blur-lg"
        >
          Get Started
        </button>
      </div>
      <div class="flex flex-col gap-5 items-center">
        <div class="">
          <div data-aos="fade-up" data-aos-delay="700" class="xl:block hidden">
            <UseTabsImage />
          </div>
          <div data-aos="fade-up" data-aos-delay="700" class="xl:hidden block">
            <img src="/cms.webp" alt="" class="rounded-2xl mt-[62px]" />
          </div>
        </div>
        <button
          data-aos="fade-up"
          data-aos-delay="100"
          class="group group-hover:before:duration-500 group-hover:after:duration-500 after:duration-500 hover:border-rose-300 hover:before:[box-shadow:_20px_20px_20px_30px_#a21caf] duration-500 before:duration-500 hover:duration-500 underline underline-offset-2 hover:after:-right-8 hover:before:right-12 hover:before:-bottom-8 hover:before:blur hover:underline hover:underline-offset-4 origin-left hover:decoration-2 hover:text-rose-300 relative bg-neutral-800 h-16 w-64 border text-left p-3 text-gray-50 text-base font-bold rounded-full overflow-hidden before:absolute before:w-12 before:h-12 before:content[''] before:right-1 before:top-1 before:z-10 before:bg-violet-500 before:rounded-full before:blur-lg after:absolute after:z-10 after:w-20 after:h-20 after:content[''] after:bg-rose-300 after:right-8 after:top-3 after:rounded-full after:blur-lg"
        >
          Try Now →
        </button>
      </div>
    </div>
  </div>
</template>
