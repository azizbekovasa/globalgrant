<script setup lang="ts">

</script>

<template>
  <div class="bg-[#ddceff]">
    <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center">
      <div class="lg:w-0 lg:flex-1">
        <h2 class="text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
          Sign up for our newsletter
        </h2>
        <p class="mt-3 max-w-3xl text-lg leading-6 text-gray-500">
          Get the latest updates on new arrivals, global growth journeys, and connect hub.
        </p>
      </div>
      <div class="mt-8 lg:mt-0 lg:ml-8">
        <form class="sm:flex">
          <label for="email-address" class="sr-only">Email address</label>
          <input id="email-address" name="email" type="email" autocomplete="email" required class="w-full px-5 py-3 border border-gray-300 shadow-sm placeholder-gray-400 focus:ring-pink-500 focus:border-pink-500 sm:max-w-xs rounded-md" placeholder="Enter your email">
          <div class="mt-3 rounded-md shadow sm:mt-0 sm:ml-3 sm:flex-shrink-0">
            <button type="submit" class="w-full flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white bg-violet-600  focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-pink-500">
              Subscribe
            </button>
          </div>
        </form>
        <p class="mt-3 text-sm text-gray-500">
          We care about your data. Read our
          <a href="#" class="font-medium text-violet-600 underline">
            Privacy Policy
          </a>.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>