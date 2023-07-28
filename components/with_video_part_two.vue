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
        <video muted  controls autoplay class="mx-auto text-center border-4  rounded-lg border-black"  src="https://nuxt-sieraf.chbk.run/vid/2.MP4" >
          Your browser does not support the video tag.
        </video>
      </div>

      <div class="max-w-2xl mx-auto mx-auto text-center bg-cyan-100  pt-12 px-4  rounded-t-2xl  lg:max-w-7xl  px-8 lg:grid lg:gap-x-8">
        <div class="lg:col-start-2 lg:mx-48">

          <p class="mt-4 text-gray-500 text-2xl font-extrabold lg:mx-16" style="text-align: justify">

            چرا باید کمک کنیم؟

          </p>
          <p class="mt-4 text-gray-500 lg:mx-16" style="text-align: justify">


            جامعه انسانی از مردان و زنان تشکیل شده ،  نیمی از جمعیت دنیا را زنان تشکیل می دهند و آن هم باید به سهم خود در پیشرفت کشورشان و رشد اقتصادی و اجتماعی پویا و فعال باشند. توجه به این نکته دلیل محکمی برای این مشارکت می باشد. و از این جمعیت در صدی به بانوان و زنان دارای معلولیت اختصاصی پیدا میکند که آنها نیز باید به اندازه توانایی خود در این راه کمک کننده و با در نظر گرفتن این مطلب میتوان به علت کمک در رشد این گروه گام برداشت و دلایل زیر را مطرح نمود.
         <br/>
             اصلی ترین علت: کمک به ایجاد خود باوری و تصور مثبت و حفظ اعتماد به نفس به گروه هدف که به علت مشکلات فرهنگی و اجتماعی این گروه کمتر خود را باور دارند.

            <br/>
             ایجاد زمینه مشارکت گروه هدف در فعالیتهای اجتماعی  اقتصادی تولیدی با در نظر گرفتن سطح توانایی آنان در جهت بهبود فعالیت اقتصادی و استقلال شان و ارتقاء توانمندیهایی معلولین
            <br/>
             رها شدن از وابستگی به دیگران و داشتن زندگی عادی مانند هر فرد دیگر در جامعه
            <br/>
             ایجاد فضای آموزش و یادگیری و حرفه آموزی با توجه به علاقه و میزان توانایی جسمی
            <br/>
            متاسفانه بدلیل ضعف در قانون با وجود اینکه این افراد به عنوان شهروند دارای حق و حقوقی می باشند ولی عملا امکانات کافی برای این افراد مهیا نیست و این مسئله نیز در رشد فعالیت اجتماعی بانوان اثر گذار می باشد.

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
