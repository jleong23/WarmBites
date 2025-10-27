<template>
  <main class="bg-gray-50 min-h-screen">
    <!-- Hero / About Section -->
    <section class="container mx-auto py-20 px-6 text-center">
      <h1 class="text-5xl font-extrabold mb-6 text-gray-800">
        About WarmBites
      </h1>
      <p class="text-lg text-gray-700 max-w-2xl mx-auto mb-4">
        Hi! I'm a beginner cook, and I know how overwhelming it can be to search
        through thousands of recipes online—some work, some don’t. That's why I
        created <span class="font-semibold text-green-600">WarmBites</span>, a
        recipe app where cooking is simplified and every recipe is tested to
        work 100% of the time.
      </p>
      <p class="text-lg text-gray-600 max-w-2xl mx-auto">
        Whether you’re just starting out in the kitchen or looking for reliable
        meal ideas, WarmBites helps you cook with confidence—no more guessing,
        no more wasted ingredients, just delicious meals you can make at home.
      </p>
    </section>

    <!-- Features Section -->
    <section class="container mx-auto py-10 px-6">
      <h2 class="text-3xl font-bold mb-8 text-gray-800 text-center">
        Why WarmBites?
      </h2>
      <div
        class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 max-w-5xl mx-auto"
      >
        <div class="p-6 bg-white rounded-lg shadow hover:shadow-lg transition">
          <h3 class="font-semibold text-xl mb-2 text-gray-800">
            Curated Recipes
          </h3>
          <p class="text-gray-600">
            Every recipe is tested to ensure it works perfectly, so you can cook
            without stress.
          </p>
        </div>

        <div class="p-6 bg-white rounded-lg shadow hover:shadow-lg transition">
          <h3 class="font-semibold text-xl mb-2 text-gray-800">
            Easy to Follow
          </h3>
          <p class="text-gray-600">
            Step-by-step instructions make cooking simple—even for beginners.
          </p>
        </div>

        <div class="p-6 bg-white rounded-lg shadow hover:shadow-lg transition">
          <h3 class="font-semibold text-xl mb-2 text-gray-800">Time-Saving</h3>
          <p class="text-gray-600">
            Spend less time searching and more time cooking delicious meals.
          </p>
        </div>
      </div>
    </section>

    <!-- Get Started Section -->
    <section class="container mx-auto py-10 px-6 text-center">
      <h2 class="text-3xl font-bold mb-4 text-gray-800">Get Started</h2>
      <p class="text-lg text-gray-700 max-w-2xl mx-auto">
        Explore recipes, find your favorites, and cook with confidence.
        WarmBites is designed to make home cooking approachable, fun, and
        stress-free for everyone.
      </p>
    </section>
  </main>
</template>

<script setup lang="ts"></script>
