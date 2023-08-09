<template>
  <div id="animation-carousel" class="relative w-full" data-carousel="static">
    <!-- Carousel wrapper -->
    <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
      <!-- Item 1 -->
      <div class="hidden duration-200 ease-linear" data-carousel-item>
        <img
          src="https://images.pexels.com/photos/5008399/pexels-photo-5008399.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
        <div
          class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-black md:block"
        >
          <h5 class="text-xl">First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p>
        </div>
      </div>
      <!-- Item 2 -->
      <div class="hidden duration-200 ease-linear" data-carousel-item>
        <img
          src="https://images.pexels.com/photos/5724030/pexels-photo-5724030.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
        <div
          class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-black md:block"
        >
          <h5 class="text-xl">First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p>
        </div>
      </div>
      <!-- Item 3 -->
      <div class="hidden duration-200 ease-linear" data-carousel-item="active">
        <img
          src="https://images.pexels.com/photos/8595878/pexels-photo-8595878.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
        <div
          class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-black md:block"
        >
          <h5 class="text-xl">First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p>
        </div>
      </div>
      <!-- Item 4 -->
      <div class="hidden duration-200 ease-linear" data-carousel-item>
        <img
          src="https://images.pexels.com/photos/7601166/pexels-photo-7601166.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
        <div
          class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-black md:block"
        >
          <h5 class="text-xl">First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p>
        </div>
      </div>
      <!-- Item 5 -->
      <div class="hidden duration-200 ease-linear" data-carousel-item>
        <img
          src="https://images.pexels.com/photos/3935333/pexels-photo-3935333.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
        <div
          class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-black md:block"
        >
          <h5 class="text-xl">First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p>
        </div>
      </div>
    </div>
    <!-- Slider controls -->
    <button
      type="button"
      class="absolute top-0 left-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none"
      data-carousel-prev
    >
      <span
        class="inline-flex items-center justify-center w-10 h-10 rounded-full group-focus:outline-none"
      >
        <svg
          class="w-4 h-4 text-white dark:text-gray-800"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 6 10"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M5 1 1 5l4 4"
          />
        </svg>
        <span class="sr-only">Previous</span>
      </span>
    </button>
    <button
      type="button"
      class="absolute top-0 right-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none"
      data-carousel-next
    >
      <span
        class="inline-flex items-center justify-center w-10 h-10 rounded-full group-focus:outline-none"
      >
        <svg
          class="w-4 h-4 text-white dark:text-gray-800"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 6 10"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="m1 9 4-4-4-4"
          />
        </svg>
        <span class="sr-only">Next</span>
      </span>
    </button>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
