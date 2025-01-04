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
      <input type="text" placeholder="Search..." class="border rounded p-2" />
      <h1 class="text-xl">Menu</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>
