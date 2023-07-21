<template>
  <div class="bg-white">
    <div class="w-full min-h-screen mx-auto pb-12 pt-12   relative   bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] ">
      <div class="text-center">
        <h2 class="text-base font-semibold text-indigo-900 tracking-wide uppercase">حمایت مالی</h2>
        <p class="mt-1 text-4xl font-extrabold text-gray-700 sm:text-5xl sm:tracking-tight text-lg lg:text-4xl"> در کنار شما دنیای بهتری خواهیم ساخت</p>
        <p class="max-w-xl mt-5 mx-auto text-lg lg:text-lg text-gray-200">شما میتوانید از طریق حساب زیر به خیریه مینو کمک مالی انجام دهید  </p>
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
