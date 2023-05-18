<<<<<<< HEAD
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
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white">Articles</nuxt-link>
                                </li>
                            </ul>
    </div>
  </div>
</nav>
=======
<template>
        <header class="bg-transparent absolute top-0 left-0 w-full flex items-center z-10">
            <div class="container">
                <div class="flex items-center justify-between relative">
                    <nuxt-link to="/">
                        <div class="px-4 flex">
                            <p class="font-bold text-xl text-primary block py-5 px-4">ZulWeb</p>
                        </div>
                    </nuxt-link>
                    <div class="flex items-center px-4">
                        <nav id="nav-menu"
                            class="hidden absolute py-5 bg-white shadow-lg rounded-lg max-w-[250px] w-full right-4 top-full lg:block lg:static lg:bg-transparent lg:max-w-full lg:shadow-none lg:rounded-none">
                            <ul class="block lg:flex">
                                <li class="group">
                                    <nuxt-link to="/"
                                        class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Home</nuxt-link>
                                </li>
                                <li class="group">
                                    <nuxt-link to="/about"
                                        class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">About</nuxt-link>
                                </li>
                                <li class="group">
                                    <nuxt-link to="/article"
                                        class="text-base text-dark py-2 mx-8 flex group-hover:text-primary">Articles</nuxt-link>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </div>
        </header>
>>>>>>> 11a48b8d2db21b78f3a5f4e2b386c81ddc9e5edb
</template>