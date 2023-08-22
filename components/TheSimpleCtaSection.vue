<template>
    <div class="relative bg-indigo-200 overflow-hidden" dir="ltr">
      <div class="bg-gray-800 pt-16 pb-32 sm:pt-24 lg:pt-40 lg:pb-48">
        <div class=" relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 sm:static" dir="rtl">
          <div>
            <p style="text-align: justify ; line-height: 30px;" id="sale-headineg" class="font-bold tracking-tight text-gray-50 text-sm md:text-4xl block md:hidden">

              در حال حاضر این موسسه خیریه بعنوان یکی از پرچمداران کارآفرینی اجتماعی در اجرا و توسعه این فرهنگ نوین با ایجاد  فرصت شغلی تولیدی برای نابینا و ناشنوایان خراسان شمالی بعنوان الگویی قابل استناد در سازمان بهزیستی و نیز بین موسسات خیریه همکار در حوزه توانمند سازی اجتماعی معلولین می باشد.
            </p>
            <p class="font-bold tracking-tight text-white text-gray-50 hidden md:block">
              با دست های مهربانتان یاری گر کسی باشید که هیچ نقشی در تعین سرنوشت خود نداشته اند
              <br/>
              <br />
              مطمئن باشید به زودی به اجرتان به بهترین نحو ممکن می رسید
            </p>
            <div class="mt-6 text-base">
              <router-link to="/shop" class="font-semibold text-white">
                <span aria-hidden="true" > 	&larrhk;</span>
                مشاهده محصولات مینو
              </router-link>
            </div>
          </div>
          <div class=" hidden lg:block">
            <div class="mt-10 hidden lg:block">
              <!-- Decorative image grid -->
              <div aria-hidden="true" class="pointer-events-none lg:absolute lg:inset-y-0 lg:max-w-7xl lg:mx-auto lg:w-full">
                <div class="absolute transform sm:left-0 sm:top-0 sm:translate-x-8 lg:left-0 lg:top-1/2 lg:-translate-y-1/2 lg:-translate-x-8">
                  <div class="flex items-center space-x-6 lg:space-x-8 lg:space-x-reverse">
                    <div class="flex-shrink-0 grid grid-cols-1 gap-y-6 lg:gap-y-8">
                      <div class="w-44 h-64 rounded-lg overflow-hidden sm:opacity-0 lg:opacity-100">
                        <img src="~/public/prod/1.jpg" alt="" class="w-full h-full object-center object-cover rounded-lg" />
                      </div>
                      <div class="w-44 h-64 rounded-lg overflow-hidden mx-2 ">
                        <img src="~/public/prod/4.jpg" alt="" class="w-full h-full object-center object-cover" />
                      </div>
                    </div>
                    <div class="flex-shrink-0 grid grid-cols-1 gap-y-6 lg:gap-y-8">
                      <div class="w-44 h-64 rounded-lg overflow-hidden">
                        <img src="~/public/prod/6.jpg" alt="" class="w-full h-full object-center object-cover" />
                      </div>
                      <div class="w-44 h-64 rounded-lg overflow-hidden">
                        <img src="~/public/prod/6.jpg" alt="" class="w-full h-full object-right object-cover" />
                      </div>
                      <div class="w-44 h-64 rounded-lg overflow-hidden">
                        <img src="~/public/prod/9.jpg" alt="" class="w-full h-full object-right object-cover" />
                      </div>
                    </div>
                    <div class="flex-shrink-0 grid grid-cols-1 gap-y-6 lg:gap-y-8">
                      <div class="w-44 h-64 rounded-lg overflow-hidden">
                        <img src="~/public/prod/9.jpg" alt="" class="w-full h-full object-center object-cover" />
                      </div>
                      <div class="w-44 h-64 rounded-lg overflow-hidden">
                        <img src="~/assets/prod/6.jpg" alt="" class="w-full h-full object-center object-cover" />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
name: "TheSimpleCtaSection"
}
</script>

<style scoped>

</style>
