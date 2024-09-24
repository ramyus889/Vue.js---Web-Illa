<script>
export default {
  name: 'UseDataSource',
  mounted() {
    document.title = 'Integrations dev';
  }
};
</script>
<template>
  <div class="flex flex-col gap-7">
    <div class="flex lg:flex-row flex-col gap-10 mt-[160px] items-center">
      <div class="flex flex-col gap-4 max-w-[570px]">
        <div data-aos="fade-up" data-aos-delay="100" class="text-[48px] leading-[56px] font-bold">
          Connect to any data source
        </div>
        <div data-aos="fade-up" data-aos-delay="300" class="leading-[24px]">
          With the ability to connect to mainstream databases or any data connected through APIs,
          ILLA Cloud allows developers to tightly integrate data obtained from the back-end with
          front-end components. This enables developers to easily write data calls and achieve
          extensive information interaction by adding resources and actions to response to user
          events.
        </div>
      </div>
      <div data-aos="fade-up" data-aos-delay="500" class="">
        <img src="/integrate/dataSource.svg" alt="" />
      </div>
    </div>
    <div class="">
      <button
        data-aos="fade-up"
        data-aos-delay="700"
        class="lg:px-[32px] lg:w-[15rem] w-full lg:mt-[0px] mt-[40px] py-[10px] bg-[#654AEC] text-white rounded-[8px] font-bold text-[20px]"
      >
        Try for Free
      </button>
    </div>
  </div>
</template>
