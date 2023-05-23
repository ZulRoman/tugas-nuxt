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
                                    <p class="font-bold text-xl" v-if="item.discount != 0">Rp. {{
                                        item.price
                                    }}</p>
                                    <p class="text-base mt-2" v-if="item.diskon === 0"></p>
                                    <p class="font-bold text-base mt-2" v-else>Diskon: {{ item.discount }}</p>
                                    <div class="flex gap-2 w-full font-bold">
                                        <p class="">Rating : {{ item.rating }}/10</p>
                                    </div>
                                    <p class="font-bold">Terjual : {{ item.sold }}</p>
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