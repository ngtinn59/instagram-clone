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
          placeholder="Search"
        />
      </div>
      <div class="flex space-x-4 items-center">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="size-6 cursor-pointer hover:scale-125 transition-transform duration-200 ease-out hidden md:inline-flex"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="m2.25 12 8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25"
          />
        </svg>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="size-6 cursor-pointer hover:scale-125 transition-transform duration-200 ease-out"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
          />
        </svg>
        <img
          class="h-10 rounded-full cursor-pointer hover:scale-125"
          src="https://scontent.fsgn23-1.fna.fbcdn.net/v/t39.30808-6/276317378_3199421297046903_762311942076936829_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeFoMG0Gqo6t8PcxnnkzSEygKuADJqIEz4Uq4AMmogTPhTF3lK8zVKmjiDYx6MT5AS2tk6Qh8uRrunQEfutriLyJ&_nc_ohc=UOTjGvsrSVYQ7kNvgES5Abs&_nc_oc=Adg_49R-L1PgAL44Qjuicd88muQr_LscFujmE46Ng7jySLnqAPF3POXs1geSRYTKz1KC6i0TIR9q1xdnwPS0fOg3&_nc_zt=23&_nc_ht=scontent.fsgn23-1.fna&_nc_gid=AR_kJPHuSZ7tIsvyjMabeN7&oh=00_AYA5YAlfqSbi0gOAvD2cLgv9aO26HzUn0A7CHzG5aUd-sA&oe=677FE47D"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>
