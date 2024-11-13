<script setup>
import { useRoute } from 'vue-router';
import UseDrawer from './UseDrawer.vue';

const useClass = 'transition-all hover:undeline';
const route = useRoute();

function isActive(path) {
  return route.path === path ? 'underline' : '';
}
</script>

<template>
  <div class="fixed top-0 left-0 right-0 z-50">
    <header
      class="flex justify-between px-[40px] py-[15px] items-center backdrop-filter backdrop-blur-[15px] bg-black bg-opacity-50"
    >
      <div class="flex items-center gap-5">
        <RouterLink to="/" :class="[useClass, isActive('/')]">
          <svg
            width="43"
            height="20"
            viewBox="0 0 43 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="w-[51px] h-[24px]"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M7.5 0H13v20H7.5V0ZM0 7.5h5.5V20H0V7.5ZM20.5 0H15v20h5.5V0Z"
              fill="#fff"
            ></path>
            <path fill="#FF58BE" d="M0 0h5.5v5.5H0z"></path>
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M37 10a4.5 4.5 0 1 1-9 0 4.5 4.5 0 0 1 9 0Zm0 8.933A9.959 9.959 0 0 1 32.5 20c-5.523 0-10-4.477-10-10s4.477-10 10-10 10 4.477 10 10v10H37v-1.067Z"
              fill="#fff"
            ></path>
          </svg>
        </RouterLink>
        <div class="lg:flex hidden gap-[8px] items-center">
          <RouterLink to="/illa-flow" :class="[useClass, isActive('/illa-flow')]" class="px-[16px] font-bold text-[14px]">ILLA Flow</RouterLink>
          <RouterLink to="/Integrations" :class="[useClass, isActive('/Integrations')]" class="px-[16px] font-bold text-[14px]"
            >Integrations</RouterLink
          >
        </div>
      </div>
      <div class="block lg:hidden"><UseDrawer /></div>
      <div class="items-center hidden gap-5 lg:flex">
        <a
          href="#"
          class="relative flex items-center justify-center h-12 p-2 overflow-hidden font-extrabold duration-500 cursor-pointer group text-sky-50 w-52 rounded-2xl bg-sky-800"
        >
          <div
            class="absolute z-10 w-48 h-48 transition-all duration-500 ease-in-out delay-150 rounded-full group-hover:scale-150 bg-sky-900 group-hover:delay-75"
          ></div>
          <div
            class="absolute z-10 w-40 h-40 transition-all duration-500 ease-in-out delay-150 rounded-full group-hover:scale-150 bg-sky-800 group-hover:delay-100"
          ></div>
          <div
            class="absolute z-10 w-32 h-32 transition-all duration-500 ease-in-out delay-150 rounded-full group-hover:scale-150 bg-sky-700 group-hover:delay-150"
          ></div>
          <div
            class="absolute z-10 w-24 h-24 transition-all duration-500 ease-in-out delay-150 rounded-full group-hover:scale-150 bg-sky-600 group-hover:delay-200"
          ></div>
          <div
            class="absolute z-10 w-16 h-16 transition-all duration-500 ease-in-out delay-150 rounded-full group-hover:scale-150 bg-sky-500 group-hover:delay-300"
          ></div>
          <p class="z-10 font-bold">Get Started For Free</p>
        </a>
      </div>
    </header>
  </div>
</template>
