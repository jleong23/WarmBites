<template>
  <main>
    <section class="container py-20">
      <h1 class="text-6xl font-extrabold mb-6 text-balance">About Nuxtcipes:</h1>
      <p class="text-xl font-extrabold mb-6 text-balance max-w-screen-lg">
        Nuxtcipes is a recipe application based on the dummyJSON API, created by John Komarnicki for
        the <span class="font-bold">Build Modern Apps with Nuxt</span> course.
      </p>
    </section>

    <div>
      <h1 class="text-xl font-bold px-20 text-green-400 ">Testing Flex</h1>
      <div class="flex gap-1 ">
        <div class="p-5 bg-red-400">Item 1</div>

        <div class="p-5 bg-red-900">Item 2</div>

        <div class="px-5 bg-red-500">
          <div>
            Item 3 
          </div>
          <div>
            Item 4
          </div>
        </div>
      </div>
    </div>

    <div class="flex items-center space-x-3 h-48 bg-gray-500 mt-5">
      <h1 class="text-xl text-red-50">Testing self-start</h1>
      <div class="bg-blue-500 w-16 h-16">Hi</div>
      <div class="bg-red-500 w-16 h-16 self-start ">Bye</div>
      <div class="bg-green-500 w-16 h-16">Bye</div>
    </div>

    <div class="flex mt-10 ">
      <div class="order-2 bg-blue-500 p-4">Item 1</div>
      <div class="order-1 bg-red-500 p-4"> Item 2</div>
      <div class="order-0 bg-green-500 p-4"> Item 3</div>
    </div> 
  </main>
</template>

<script setup lang="ts"></script>