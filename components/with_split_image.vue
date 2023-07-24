<!--
  This example requires Tailwind CSS v2.0+

  This example requires some changes to your config:

  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/aspect-ratio'),
    ],
  }
  ```
-->
<template>
  <div class="bg-white">
    <section aria-labelledby="features-heading" class="relative">
      <div class="m-5 p-5 rounded-lg  mx-auto text-center">
        <video muted  controls autoplay class="mx-auto text-center border-4  rounded-lg border-black"  src="https://nuxt-sieraf.chbk.run/vid/1.MP4" >
          Your browser does not support the video tag.
        </video>
        <p class=" text-xl mt-3 font-extrabold text-gray-900 tracking-tight"> خانم جزایری</p>
        <h2 id="features-heading" class="font-medium mt-2 text-gray-500"> مدیر خیریه</h2>
      </div>

      <div class="max-w-2xl mx-auto mx-auto text-center bg-cyan-100  pt-12 px-4  rounded-t-2xl  lg:max-w-7xl  px-8 lg:grid lg:gap-x-8">
        <div class="lg:col-start-2">

          <p class="mt-4 text-gray-500 text-2xl font-extrabold lg:mx-16" style="text-align: justify">

           اهداف کلی

          </p>
          <p class="mt-4 text-gray-500 lg:mx-16" style="text-align: justify">

            آموزش حرفه ای ویژه متناسب با علاقه و سطح توانایی فرد مورد نظر
            <br/>
            <br/>
            کمک مالی برای تحصیل و آموزش عالی
            <br/>
            <br/>

            توان بخشی و کمک برای تهیه وسایل کمکی مانند ویلچر و سمعک و سایر موارد
            <br/>
            <br/>
            کمک هزینه مسکن
            <br/>
            <br/>
            کمک هزینه درمان (جراحی و فیزیوتراپی و غیره)
            <br/>
            <br/>
            وسایل آسان کننده زندگی و تعمیرات ساختمان
          </p>

          <dl class="mt-10 grid grid-cols-1 gap-y-10 gap-x-8 text-sm sm:grid-cols-2">
            <div v-for="feature in features" :key="feature.name">
<!--              <dt class="font-medium text-gray-900">{{ feature.name }}</dt>-->
<!--              <dd class="mt-2 text-gray-500">{{ feature.description }}</dd>-->
            </div>
          </dl>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
const features = [
  {
    name: 'Durable',
    description: 'The leather cover and machined steel disc binding stand up to daily use for years to come.',
  },
  {
    name: 'Refillable',
    description: 'Buy it once and refill as often as you need. Subscribe and save on routine refills.',
  },
  {
    name: 'Thoughtfully designed',
    description:
      'The comfortable disc binding allows you to quickly rearrange pages or combine lined, graph, and blank refills.',
  },
  { name: 'Locally made', description: 'Responsibly and sustainably made real close to wherever you are, somehow.' },
]

export default {
  setup() {
    return {
      features,
    }
  },
}
</script>
