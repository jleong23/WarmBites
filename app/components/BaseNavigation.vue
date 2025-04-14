<template>

  <header class="py-4 border-b">
    <nav class="flex container items-center">

      <!--Making "NuxtCipes" into a NuxtLink that can bring us to the "IndexPage"(home) --- -->      
      <NuxtLink to="/" class="flex gap-1 items-center">
        <span class="text-3xl font-bold">Nuxtcipes</span>
      </NuxtLink>
      <!-- ------------------------------------------------------------------- -->

      <ul class="flex gap-6 ml-auto text-xl font-bold capitalize">
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>

</template>2
  
<script setup lang="ts">

</script>
