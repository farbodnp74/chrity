<template>
  <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">تازه های مینو</h2>
        <p class="mt-2 text-lg leading-8 text-gray-600"></p>
      </div>
      <div class="mx-auto mt-10 grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 border-t border-gray-200 pt-10 sm:mt-16 sm:pt-16 lg:mx-0 lg:max-w-none lg:grid-cols-3">
        <article v-for="post in posts" :key="post.id" class="bg-gray-100 m-3 p-3 rounded-xl flex max-w-xl flex-col items-start justify-between">
          <div class="flex items-center gap-x-4 text-xs">
            <time :datetime="post.datetime" class="text-gray-500">{{ post.date }}</time>
            <a :href="post.category.href" class="relative z-10 rounded-full bg-gray-50 px-3 py-1.5 font-medium text-gray-600 hover:bg-gray-100">{{ post.category.title }}</a>
          </div>
          <div class="group relative">
            <h3 class="mt-3 text-lg font-semibold leading-6 text-gray-900 group-hover:text-gray-600">
              <a :href="post.href">
                <span class="absolute inset-0" />
                {{ post.title }}
              </a>
            </h3>
            <p class="mt-5 line-clamp-3 text-sm leading-6 text-gray-600">{{ post.description }}</p>
          </div>
          <div class="relative mt-8 flex items-center gap-x-4">
            <img :src="post.author.imageUrl" alt="" class="h-10 w-10 rounded-full bg-gray-50" />
            <div class="text-sm leading-6">
              <p class="font-semibold text-gray-900">
                <a :href="post.author.href">
                  <span class="absolute inset-0" />
                  {{ post.author.name }}
                </a>
              </p>
              <p class="text-gray-600">{{ post.author.role }}</p>
            </div>
          </div>
        </article>
      </div>
    </div>
  </div>
</template>

<script setup>
const posts = [
  {
    id: 1,
    title: 'بازدید دکتر پاکمهر',
    href: '#',
    description:
        'توضیحی درباره دکتر پاکمهر',
    date: '13 تیر',
    datetime: '2023-07-01',
    category: { title: 'news', href: '#' },
    author: {
      name: 'فربد نصیری پرتوی',
      role: '',
      href: '#',
      imageUrl:
          'https://mag.bonyaddanesh.org/wp-content/uploads/2021/12/%D8%A8%D8%B2%D8%B1%DA%AF%D8%AA%D8%B1%DB%8C%D9%86.jpg',
    },
  },
  {
    id: 1,
    title: 'بازدید دکتر پاکمهر',
    href: '#',
    description:
        'توضیحی درباره دکتر پاکمهر',
    date: '13 تیر',
    datetime: '2023-07-01',
    category: { title: 'news', href: '#' },
    author: {
      name: 'فربد نصیری پرتوی',
      role: '',
      href: '#',
      imageUrl:
          'https://mag.bonyaddanesh.org/wp-content/uploads/2021/12/%D8%A8%D8%B2%D8%B1%DA%AF%D8%AA%D8%B1%DB%8C%D9%86.jpg',
    },
  },
  {
    id: 1,
    title: 'بازدید دکتر پاکمهر',
    href: '#',
    description:
        'توضیحی درباره دکتر پاکمهر',
    date: '13 تیر',
    datetime: '2023-07-01',
    category: { title: 'news', href: '#' },
    author: {
      name: 'فربد نصیری پرتوی',
      role: '',
      href: '#',
      imageUrl:
          'https://mag.bonyaddanesh.org/wp-content/uploads/2021/12/%D8%A8%D8%B2%D8%B1%DA%AF%D8%AA%D8%B1%DB%8C%D9%86.jpg',
    },
  },
  // More posts...
]
</script>
