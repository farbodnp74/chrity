
<template>
  <div>
    <NuxtLayout name="custom">
    <div class="bg-white" dir="rtl">
      <div class="mx-auto max-w-2xl px-4 py-16 sm:px-6 sm:py-24 lg:max-w-7xl lg:px-8">
        <h2 class="text-2xl font-bold tracking-tight text-gray-900">گالری خیریه مینو</h2>

        <div class="mt-6 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 lg:grid-cols-4 xl:gap-x-8">
          <div v-for="product in products" :key="product.id" class="group relative">

            <div class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-md bg-gray-200 lg:aspect-none group-hover:opacity-75 lg:h-80">
              <img :src="'https://nuxt-sieraf.chbk.run/prod/'+product.imageSrc" :alt="product.imageAlt" class="h-full w-full object-cover object-center lg:h-full lg:w-full" />
            </div>
          </div>
        </div>
      </div>
    </div>
    </NuxtLayout>
  </div>
</template>



<script setup>
const products = [

  {
    id: 4,
    imageSrc: '5.jpg',
    imageAlt: "خیریه مینو",

  },
  {
    id: 5,
    imageSrc: '6.jpg',
    imageAlt: "خیریه مینو",

  },
  {
    id: 11,
    imageSrc: '11.jpg',
    imageAlt: "خیریه مینو",

  },

  {
    id: 12,
    imageSrc: '12.jpg',
    imageAlt: "خیریه مینو",

  },
  {
    id: 14,
    imageSrc: '14.jpg',
    imageAlt: "خیریه مینو",

  },
  // More products...
]
</script>
