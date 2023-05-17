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
</template>