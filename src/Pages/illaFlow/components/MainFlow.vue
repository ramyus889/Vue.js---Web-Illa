<script>
export default {
  name: 'MainFlow',
  mounted() {
    document.title = 'illa Flow dev';
  }
};
</script>
<template>
  <div class="flex place-content-center mt-[160px]">
    <div class="">
      <div
        data-aos="fade-up"
        data-aos-delay="100"
        class="text-[24px] text-start bg-gradient-to-r from-[#24FFFF] to-[#C5FFFF] bg-clip-text text-transparent font-bold"
      >
        ILLA Flow
      </div>
      <div
        data-aos="fade-up"
        data-aos-delay="300"
        class="md:text-[64px] text-[32px] md:leading-[70px] leading-[38px] font-bold mt-[16px]"
      >
        Surpassing developers' expectations, effortlessly automating workflows
      </div>
      <div data-aos="fade-up" data-aos-delay="400" class="max-w-[304px] mt-[40px]">
        <button class="py-[14px] w-full bg-[#654aec] rounded-[8px]">Get Started for free</button>
      </div>
      <div data-aos="fade-up" data-aos-delay="100" class="">
        <img src="/flow/screen1.png" alt="" class="mt-[300px]" />
      </div>
    </div>
  </div>
</template>
