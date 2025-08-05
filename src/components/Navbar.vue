<template>
    <div>
  <div class="bg-black text-white text-sm text-center py-2">
    Summer Sale For All Swim Suits And Free Express Delivery - OFF 50%!
    <a href="#" class="text-blue-400 font-bold ml-1">ShopNow</a>
  </div>


  <header class="flex items-center justify-between px-6 py-4 border-b relative z-10">

    <div class="text-2xl font-bold">Exclusive</div>


    <nav class="space-x-6 hidden md:flex">
      <router-link to="/" class="text-gray-700 hover:text-black">Home</router-link>
      <router-link to="/contact" class="text-gray-700 hover:text-black">Contact</router-link>
      <router-link to="/about" class="text-gray-700 hover:text-black">About</router-link>
      <a href="#" class="text-gray-700 hover:text-black">Sign Up</a>
    </nav>


    <div class="flex items-center space-x-4">

      <div class="relative hidden sm:block">
        <input type="text" placeholder="What are you looking for?"
          class="border rounded-full px-4 py-1 pl-10 w-64 text-sm">
        <svg class="w-4 h-4 text-gray-400 absolute left-3 top-2.5" fill="none" stroke="currentColor" stroke-width="2"
          viewBox="0 0 24 24">
          <path d="M21 21l-4.35-4.35m0 0A7.5 7.5 0 104.5 4.5a7.5 7.5 0 0012.15 12.15z"></path>
        </svg>
      </div>


      <button>
        <svg class="w-6 h-6 text-gray-700 hover:text-black" fill="none" stroke="currentColor" stroke-width="2"
          viewBox="0 0 24 24">
          <path
            d="M4.318 6.318a4.5 4.5 0 016.364 0L12 7.636l1.318-1.318a4.5 4.5 0 116.364 6.364L12 21.364l-7.682-7.682a4.5 4.5 0 010-6.364z">
          </path>
        </svg>
      </button>


      <button>
        <svg class="w-6 h-6 text-gray-700 hover:text-black" fill="none" stroke="currentColor" stroke-width="2"
          viewBox="0 0 24 24">
          <path
            d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13l-1.5 7h13L17 13M7 13H5.4M17 13l1.5 7M9 21a1 1 0 11-2 0 1 1 0 012 0zm10 0a1 1 0 11-2 0 1 1 0 012 0z">
          </path>
        </svg>
      </button>


      <button class="md:hidden" onclick="document.getElementById('mobile-menu').classList.toggle('hidden')">
        <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path d="M4 6h16M4 12h16M4 18h16"></path>
        </svg>
      </button>
    </div>
  </header>

    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>
