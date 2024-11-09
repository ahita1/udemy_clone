<template>
  <header class="flex items-center justify-between px-4 py-2 bg-white shadow-md">
    <!-- Left Section: Logo and Categories -->
    <div class="flex items-center space-x-4">
      <!-- Logo -->
      <img src="@/assets/image.png" alt="Udemy Logo" class="w-24 h-auto" />

      <!-- Categories Link -->
      <a href="#" class="text-gray-700 font-medium hover:text-black">
        Categories
      </a>
    </div>

    <!-- Center Section: Search Bar -->
    <div class="flex-grow max-w-md mx-4">
      <div class="relative">
        <input
          type="text"
          placeholder="Search for anything"
          class="w-full px-4 py-2 border rounded-full focus:outline-none focus:ring focus:ring-purple-300"
        />
        <span class="absolute top-0 right-4 text-gray-500 flex items-center h-full">
          🔍 <!-- Replace with search icon if you have an icon library -->
        </span>
      </div>
    </div>

    <!-- Right Section: Links and Buttons -->
    <div class="flex items-center space-x-4">
      <!-- Udemy Business and Teach Links -->
      <a href="#" class="text-gray-700 font-medium hover:text-black">
        Udemy Business
      </a>
      <a href="#" class="text-gray-700 font-medium hover:text-black">
        Teach on Udemy
      </a>

      <!-- Cart Icon -->
      <a href="#" class="text-gray-700 hover:text-black">
        🛒 <!-- Replace with cart icon if you have an icon library -->
      </a>

      <!-- Log In Button -->
      <button class="text-gray-700 font-medium hover:text-black">
        Log in
      </button>

      <!-- Sign Up Button -->
      <button class="px-4 py-2 bg-gray-900 text-white font-medium rounded hover:bg-gray-700">
        Sign up
      </button>
    </div>
  </header>
</template>

<script>
export default {
  name: 'UdemyHeader',
}
</script>

<style scoped>
/* Add custom styles if needed */
</style>
