<script setup lang="ts">

</script>

<template>
  <div class="bg-white">
    <header class="bg-[#984dff] text-white text-center py-12">
      <h1 class="text-4xl font-bold mt-16">Contact Us</h1>
    </header>
    <section class="text-center py-12 px-4">
      <h2 class="text-2xl font-bold">Get In Touch</h2>
      <p class="mt-4 text-gray-700 max-w-2xl mx-auto">We are here to help you. Reach out to us via any of the following methods.</p>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8 mt-8 animate-fadeIn">
        <div class="p-4 shadow-lg rounded-lg bg-[#dfd2ff] transition-colors">
          <h3 class="text-xl font-bold">Call Us</h3>
          <p class="text-gray-700 mt-2">+1 123 456 7890</p>
        </div>
        <div class="p-4 shadow-lg rounded-lg bg-[#dfd2ff] transition-colors">
          <h3 class="text-xl font-bold">Email Us</h3>
          <p class="text-gray-700 mt-2">contact@wisedoctors.com</p>
        </div>
        <div class="p-4 shadow-lg rounded-lg bg-[#dfd2ff] transition-colors">
          <h3 class="text-xl font-bold">Visit Us</h3>
          <p class="text-gray-700 mt-2">123 Health St, Wellness City</p>
        </div>
      </div>
    </section>
    <section class="bg-gray-100 py-12 px-4">
      <h2 class="text-2xl font-bold text-center">Send Us A Message</h2>
      <form class="max-w-2xl mx-auto mt-8 space-y-8">
        <div>
          <label htmlFor="name" class="block text-gray-700 font-bold">Name</label>
          <input type="text" id="name" class="w-full mt-2 p-3 border rounded-lg shadow-sm focus:outline-none focus:ring-2 focus:[#984dff] transition" />
        </div>
        <div>
          <label htmlFor="email" class="block text-gray-700 font-bold">Email</label>
          <input type="email" id="email" class="w-full mt-2 p-3 border rounded-lg shadow-sm focus:outline-none focus:ring-2 focus:[#984dff] transition" />
        </div>
        <div>
          <label htmlFor="message" class="block text-gray-700 font-bold">Message</label>
          <textarea id="message" rows="5" class="w-full mt-2 p-3 border rounded-lg shadow-sm focus:outline-none focus:ring-2 focus:[#984dff] transition"></textarea>
        </div>
        <button type="submit" class="w-full bg-[#984dff] text-white py-3 rounded-lg shadow-lg hover:bg-[#af80ff] transition-colors">Send Message</button>
      </form>
    </section>
    <section class="text-center py-12 px-4">
      <h2 class="text-2xl font-bold">Frequently Asked Questions</h2>
      <div class="mt-8">
        <div class="p-4 border rounded-lg shadow-md transition transform hover:scale-100 scale-90">
          <h3 class="text-xl font-bold">How do I begin my journey to study abroad with GlobalGrant?</h3>
          <p class="mt-2 text-gray-700">Create a free profile and use our filters to explore universities and scholarships matching your goals </p>
        </div>
        <div class="p-4 border rounded-lg shadow-md transition transform hover:scale-100 scale-90 mt-4">
          <h3 class="text-xl font-bold">What are typical application requirements for international university?</h3>
          <p class="mt-2 text-gray-700">Generally, you'll need yr grades, recommendation letters, a personal essay, and an English test score.</p>
        </div>
        <div class="p-4 border rounded-lg shadow-md transition transform hover:scale-100 scale-90  mt-4">
          <h3 class="text-xl font-bold">Are there fully funded options?</h3>
          <p class="mt-2 text-gray-700">Yes, fully funded scholarships are available, which our filters can help you find. </p>
        </div>
      </div>
    </section>
    <footer class="bg-[#af80ff] text-white text-center py-8">
      <p>&copy; Copyright Your Company Name 2024 . All rights reserved. Made By Binary Boats⛵.</p>
    </footer>
  </div>
</template>

<style scoped>

</style>