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

            راههای مختلف کمک رسانی

          </p>
          <p class="mt-4 text-gray-500 lg:mx-16" style="text-align: justify">

            از بدو تاسیس خیریه مینو تاکنون به شکل های مختلف افرادی که داوطلب کمک بوده اند در کنار ما حضور داشته اند. که کوتاه به آنها اشاره خواهد شد.
           <br>
            الف: کمکهای فکری و طرح ایده و کمک برای آموزش این عزیزان و حرفه آموزی و تعیین سطح توانایی شان
            در مرحله اول و بعد آموزش فرد به فرد عزیزانی که در حال حاضر در خیریه مشغول به کار هستند که اینکار توسط معلمین با تجربه و همچنین کسانی که توانایی برقراری ارتباط با دختران ناشنوا را داشته باشند انجام گرفته و با آموزش و استفاده از کمک افراد متخصص تا مرحله اخذ مدرک فنی حرفه ای و ورود به دانشگاه هم پیشرفت داشته اند.
            <br>
             کمکهای مالی که به چهار طریق تاکنون انجام شده

            <br/>
            1-
             با کمکهای موردی و با توجه به شرایط پیش آمده مثلاً خرید درمان و جراحی برای گذاشتن ایمپلنت  در مجرای گوش و یا جراحی ستون فقرات دو مورد از دختران جسمی-حرکتی

            <br/>
            2-
             کمکهای دائم و ماهانه که معمولاً به مصرف هزینه های جاری مثل سرویس رفت و آمد بچه ها هزینه بیمه بازنشستگی و بیمه درمانی شان

           <br/>
            3-
            کمک هزینه تحصیلی برای تحصیل دانشگاه دختران مستعد و علاقه مند تا اخذ مدرک لیسانس
            <br/>
            4-
              واریزی به حساب خیریه

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
