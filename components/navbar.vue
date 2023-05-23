<template>
    <nav class="flex items-center sticky top-0 justify-between flex-wrap bg-gray-900 p-6">
  <div class="flex items-center flex-shrink-0 text-white mr-6">
    <img class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" src="https://png.pngitem.com/pimgs/s/2-23455_website-logo-png-transparent-background-clipart-png-transparent.png">
    <span class="font-semibold text-xl tracking-tight">ZulWeb</span>
  </div>
  <div class="block lg:hidden">
    <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
      <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
    </button>
  </div>
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow">
        <ul class="block lg:flex">
                                <li class="group">
                                    <nuxt-link to="/"
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Home</nuxt-link>
                                </li>
                                <li class="group">
                                    <nuxt-link to="/about"
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">About</nuxt-link>
                                </li>
                                <li class="group">
                                    <nuxt-link to="/article"
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Articles</nuxt-link>
                                </li>
                                <li class="group">
                                    <nuxt-link to="/produk"
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white">Produk</nuxt-link>
                                </li>
                            </ul>
    </div>
  </div>
</nav>
</template>