<template>
  <div class="bg-white">
    <div class="w-full min-h-screen mx-auto pb-12 pt-12   relative   bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] ">
      <div class="text-center">
<!--        <h2 class="text-xl font-semibold text-indigo-900 tracking-wide uppercase">حمایت مالی</h2>-->
<!--        <p class="mt-1 text-4xl font-extrabold text-gray-700 sm:text-5xl sm:tracking-tight text-lg lg:text-4xl"> در کنار شما دنیای بهتری خواهیم ساخت</p>-->
<!--        <p class="max-w-xl my-5 mx-auto text-sm lg:text-lg text-gray-200">شما میتوانید از طریق حساب زیر به خیریه مینو کمک مالی انجام دهید  </p>-->
        <div dir="rtl" class="max-w-2xl bg-cyan mx-auto mx-auto text-center bg-indigo-50  mb-12 pt-12 px-4  rounded-2xl  lg:max-w-7xl  px-8 lg:grid lg:gap-x-8">
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

<!--        <h2 class="text-xl font-semibold text-indigo-900 tracking-wide uppercase">حمایت مالی</h2>&ndash;&gt;-->
                <p class="mt-1 text-4xl font-extrabold text-gray-700 sm:text-5xl sm:tracking-tight text-lg lg:text-4xl"> در کنار شما دنیای بهتری خواهیم ساخت</p>
                <p class="max-w-xl mt-3 mx-auto text-sm lg:text-lg text-gray-200">شما میتوانید از طریق حساب زیر به خیریه مینو کمک مالی انجام دهید  </p>

        <TheAboutComponent/>
        <!--        <p class="max-w-xl mt-5 mx-auto text-lg lg:text-xl text-gray-50">میتوانید با استفاده از لینک زیر به هر مقداری به خیریه مینو کمک کنید </p>-->
<!--        <div class="mt-6 bg-indigo-300 w-fit mx-auto text-center m-2 p-2 text-gray-50 rounded-lg">-->
<!--          لینک پی پینگ-->
<!--        </div>-->
      </div>
    </div>
  </div>
</template>

<script>

import TheAboutComponent from "../components/TheAboutComponent.vue";
export default {
  name: "help",
  components: {TheAboutComponent}
}
</script>

<style scoped>

</style>
