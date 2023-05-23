<template>
        <div class="container mt-20 mb-44">
  <div>
    <section class="bg-gray-900 py-12">
    <h1 class="text-white text-center text-4xl font-bold">Cara memasak Indomie</h1>
</section>  
    </div>

<div class="flex justify-center">
<img src="https://www.indomie.com/uploads/product/category_dry-based-noodles_133948614.png" width="300px" height="200px">
</div>
<br>


<div class="flex flex-col justify-center text-lg">
<div class="flex flex-col gap-2">
    <table>
        <thead class="bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="text-white text-center text-xl font-bold">
                    Alat dan Bahan
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 ">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white text-center flex">
                    <ul class="list-decimal pl-6 text-left">
                        <li class="mb-2">Panci</li>
                        <li class="mb-2">Sendok dan Garpu</li>
                        <li class="mb-2">1 Gelas Air</li>
                        <li class="mb-2">Indomie</li>
                      </ul>
                </th>
            </tr>
        </tbody>
    </table>
    <table>
        <thead class="bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="text-white text-center text-xl font-bold">
                    Cara Memasak
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white text-center">
                    <ul class="list-decimal pl-6 text-left">
                        <li class="mb-2">Siapkan panci untuk merebus mie</li>
                        <li class="mb-2">Isi panci dengan 1 gelas air dan rebus sampai mendidih</li>
                        <li class="mb-2">Buka bungkus mie instan dan masukkan mie ke dalam air yang mendidih</li>
                        <li class="mb-2">Masak mie selama 3 menit dan sesekali dapat diaduk agar mie matang merata</li>
                        <li class="mb-2">Tuang bumbu minyak, bubuk cabai dan bumbu penyedap ke atas piring</li>
                        <li class="mb-2">Setelah mie matang, ambil mie lalu tiriskan</li>
                        <li class="mb-2">Letakkan mie yang sudah matang di atas piring isi bumbu</li>
                        <li class="mb-2">Aduk merata mie beserta bumbunya dan mie instan sudah bisa dinikmati</li>
                      </ul>
                </th>
            </tr>
        </tbody>
    </table>
    </div>
      </div>



    
<h2 class="text-2xl font-bold mb-4 text-center">Untuk selengkapnya bisa lihat video dibawah ini</h2>
<div class="px-4 sm:px-10 md:px-20 lg:px-40 xl:px-60 py-6">
    <div> 
        <iframe class="w-full h-96" src="https://www.youtube.com/embed/AkkzqcXJvvo">
    </iframe>
</div>
      </div>
<br>

<h2 class="text-2xl font-bold mb-4 text-center">Produk Indomie</h2>

<div class="flex justify-center gap-1">
<card :image="'https://www.indomie.com/uploads/product/indomie-mi-goreng-special_thumb_094906798.png'" :title="'Indomie Goreng'" />
<card :image="'https://www.indomie.com/uploads/product/indomie-mi-goreng-rendang-flavour_thumb_170333176.png'" :title="'Indomie Goreng Rendang'" />
<card :image="'https://www.indomie.com/uploads/product/indomie-mi-goreng-cabe-ijo-flavour_thumb_145129182.png'" :title="'Indomie Goreng Cabe Ijo'" />
</div>
</div>


</template>

<script setup>
const route = useRoute()
console.log(route.params.id)
</script>
