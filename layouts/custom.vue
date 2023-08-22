<template>
  <div dir="rtl">
    <TheBanner class="sticky"/>
    <TheNewHeader class="sticky top-0 z-30 lg:z-40"/>

    <main class="relative">
        <slot/>
    </main>
    <div class="  right-20 bottom-0 z-30 w-50 sticky items-center justify-center self-center my-auto text-center" dir="rtl">
      <div  class="bg-gray-200   h-32 w-32 rounded-full items-center self-center justify-center my-auto text-center" style="padding: 20px!important;">
        <a class="" referrerpolicy="origin" target="_blank" href="https://trustseal.enamad.ir/?id=366374&amp;Code=dDJh9IlxlqgArmB8bvfH"><img referrerpolicy="origin" src="https://trustseal.enamad.ir/logo.aspx?id=366374&amp;Code=dDJh9IlxlqgArmB8bvfH" alt="" style="cursor:pointer" id="dDJh9IlxlqgArmB8bvfH"></a>

      </div>
    </div>
    <TheFooter/>


  </div>

</template>
<script>
import TheBanner from "../components/TheBanner.vue";
import TheFooter from "../components/TheFooter";
import TheNewHeader from "../components/TheNewHeader";
export default {
  components: {TheNewHeader, TheFooter, TheBanner}
}
</script>
