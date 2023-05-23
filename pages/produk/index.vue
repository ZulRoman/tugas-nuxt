<template>
    <div class="w-full">
        <main class="w-10/12 mx-auto my-4">
            <section id="class">
                <h2 class="font-bold text-4xl my-6">Produk</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 gap-y-8">
                    <div class="bg-white shadow-lg rounded" v-for="item in produkData" :key="item.id">
                            <div>
                                <div>
                                    <img :src="item.image" alt="" class="w-full h-[250px] object-cover object-top">
                                </div>
                                <div class="p-4">
                                    <div>
                                        <h2 class="text-xl flex items-center font-extrabold">{{ item.name }}</h2>
                                    </div>
                                    <div>
                                        <h4 class="text-l flex items-center">{{ item.description }}</h4>
                                    </div>
                                    <p class="font-bold text-xl">Rp. {{ item.price }}</p>
                                    <p class="font-bold text-base mt-2">Diskon: {{ item.discount }}</p>
                                    <div class="flex gap-2 w-full font-bold">
                                        <p class="">Rating : {{ item.rating }}/10</p>
                                    </div>
                                    <p class="font-bold mb-4">Terjual : {{ item.sold }}</p>   
                                    <button class="bg-blue-500 hover:bg-blue-700 text-white text-xs font-bold py-2 px-4 mb-4">
                                        Beli
                                    </button>                                 
                                    <h4 class="font-bold text-xl mb-4">Komentar</h4>
                                    <div class="">
                                        <div class="flex items-center gap-2">
                                            <img src="https://static.vecteezy.com/system/resources/thumbnails/009/734/564/small/default-avatar-profile-icon-of-social-media-user-vector.jpg"
                                                class="w-[40px]" alt="">
                                            <div class="">
                                                <h4 class="font-bold text-xl">{{ item.comments.name }}</h4>
                                                <p class="text-sm">{{item.comments.date }}</p>
                                            </div>
                                        </div>
                                        <p class="p-2">{{item.comments.comment }}</p>
                                    </div>
                                </div>
                            </div>
                    </div>
                </div>
            </section>
        </main>
    </div>
</template>

<script>
import json from '@/assets/data/produk.json';
export default {
    data() {
        return {
            layouts: {
                header: "header",
                footer: "footer"
            },
            produkData: json,
        }
    },
}
</script>