<template>
  <div class="flex flex-col items-center justify-center w-full bg-white">
    <span class="mt-4 text-6xl font-bold text-black capitalize">Impact News</span>
    <div class="flex flex-row items-center justify-center w-1/2 mt-3 mb-8 text-base font-normal capitalize">
      <div class="flex flex-row items-center justify-center mx-2 text-gray-500 cursor-pointer hover:text-gray-700">
        <div class="mr-0.5">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 256 256"><path fill="currentColor" d="M208.2 123.8a5.8 5.8 0 0 1 0 8.4l-82 82a54 54 0 0 1-76.4-76.4l99.3-100.6a38 38 0 0 1 53.8 53.7l-99.3 100.6A21.9 21.9 0 0 1 88 198a22.1 22.1 0 0 1-15.6-37.6l83.3-84.6a6 6 0 0 1 8.6 8.4L81 168.9a9.6 9.6 0 0 0-3 7.1a10 10 0 0 0 17.1 7.1l99.3-100.7a26 26 0 0 0-36.8-36.8L58.3 146.3a42 42 0 0 0 59.4 59.4l82.1-81.9a5.8 5.8 0 0 1 8.4 0Z"/></svg>
        </div>
        <span class="text-sm">ePaper</span>
      </div>

      <div class="flex flex-row items-center justify-center mx-2 text-gray-500 cursor-pointer hover:text-gray-700">
        <div class="mr-0.5">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 512 512"><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" d="M368 415.86V72a24.07 24.07 0 0 0-24-24H72a24.07 24.07 0 0 0-24 24v352a40.12 40.12 0 0 0 40 40h328"/><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="32" d="M416 464a48 48 0 0 1-48-48V128h72a24 24 0 0 1 24 24v264a48 48 0 0 1-48 48Z"/><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32" d="M240 128h64m-64 64h64m-192 64h192m-192 64h192m-192 64h192"/><path fill="currentColor" d="M176 208h-64a16 16 0 0 1-16-16v-64a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16v64a16 16 0 0 1-16 16Z"/></svg>
        </div>
        <span class="text-sm">Subscribe</span>
      </div>

      <div class="flex flex-row items-center justify-center mx-2 text-gray-500 cursor-pointer hover:text-gray-700">
        <div class="mr-0.5">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 256 256"><path fill="currentColor" d="M223.7 32.3a15.9 15.9 0 0 0-15.6-4.1L21.8 80.7a16.1 16.1 0 0 0-2.6 29.9l85.7 40.5l40.5 85.7a16 16 0 0 0 14.4 9.1h1.4a15.9 15.9 0 0 0 14.1-11.6l52.5-186.4a15.9 15.9 0 0 0-4.1-15.6Zm-63.8 197.6l-39.4-83.1l41.3-41.3a8 8 0 1 0-11.3-11.3l-41.3 41.3l-83.1-39.4l186.3-52.5Z"/></svg>
        </div>
        <span class="text-sm">Newsletters</span>
      </div>

      <div class="flex flex-row items-center justify-center mx-2 text-gray-500 cursor-pointer hover:text-gray-700">
        <div class="mr-0.5">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 32 32"><path fill="currentColor" d="m29 27.586l-7.552-7.552a11.018 11.018 0 1 0-1.414 1.414L27.586 29ZM4 13a9 9 0 1 1 9 9a9.01 9.01 0 0 1-9-9Z"/></svg>
        </div>
        <span class="text-sm">Search</span>
      </div>

      <div class="flex flex-row items-center justify-center mx-2 text-gray-500 cursor-pointer hover:text-gray-700">
        <div class="mr-0.5">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"><g fill="currentColor" fill-rule="evenodd" clip-rule="evenodd"><path d="M16 9a4 4 0 1 1-8 0a4 4 0 0 1 8 0Zm-2 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0Z"/><path d="M12 1C5.925 1 1 5.925 1 12s4.925 11 11 11s11-4.925 11-11S18.075 1 12 1ZM3 12c0 2.09.713 4.014 1.908 5.542A8.986 8.986 0 0 1 12.065 14a8.984 8.984 0 0 1 7.092 3.458A9 9 0 1 0 3 12Zm9 9a8.963 8.963 0 0 1-5.672-2.012A6.992 6.992 0 0 1 12.065 16a6.991 6.991 0 0 1 5.689 2.92A8.964 8.964 0 0 1 12 21Z"/></g></svg>
        </div>
        <span class="text-sm">Profile</span>
      </div>

    </div>
    <MainNavigation />
  </div>
</template>
<script setup>
import MainNavigation from '../navigation/MainNavigation.vue';

</script>
