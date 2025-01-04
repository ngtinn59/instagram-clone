<template>
  <div class="sticky top-0 bg-white shadow-md">
    <div
      class="flex justify-between h-24 items-center mx-4 xl:max-w-6xl xl:mx-auto"
    >
      <h1 class="cursor-pointer w-24 hidden lg:inline-grid">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Instagram_logo.svg/2560px-Instagram_logo.svg.png"
          alt="instagram-logo"
        />
        <h1 class="cursor-pointer w-10 lg:hidden">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/1200px-Instagram_logo_2016.svg.png"
            alt="instagram-logo"
          />
        </h1>
      </h1>
      <div class="relative mt-1">
        <div class="absolute top-2 left-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="2.5"
            stroke="currentColor"
            class="h-5 w-5 text-gray-700"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z"
            />
          </svg>
        </div>
        <input
          class="pl-10 rounded-md focus:ring-black focus:border-black bg-gray-50 border-gray-500 text-sm"
          type="text"
        />
      </div>
      <h1 class="text-xl">Menu</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>
