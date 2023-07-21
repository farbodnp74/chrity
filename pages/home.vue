<template>
  <div>
    <NuxtLayout name="custom">
      <TheHeroSectionComponent/>
      <TheSimpleCtaSection/>
<!--      <CategoriesWithImageBackgrounds/>-->
      <hr class="text-black bg-black py-0.5 lg:mx-72">
      <CategoriesWithScrollingCards/>
<!--      <TheNewsSection/>-->

<!--      <CtaPart/>-->
      <CommerceUs/>
    </NuxtLayout>
  </div>
</template>

<script>
import ProductListTallImages from "../components/ProductListTallImages";
import CategoriesWithImageBackgrounds from "../components/CategoriesWithImageBackgrounds";
import CategoriesWithScrollingCards from "../components/CategoriesWithScrollingCards";
import CategoriesWithSplitImages from "../components/CategoriesWithSplitImages";
import CommerceUs from "../components/CommerceUs.vue";
import CtaPart from "../components/CtaPart";
import TheSimpleCtaSection from "../components/TheSimpleCtaSection";
import TheHeroSectionComponent from "../components/TheHeroSectionComponent.vue";
import TheNewsSection from "../components/TheNewsSection.vue";
export default {
 components:{
   TheNewsSection,
   TheHeroSectionComponent,
   TheSimpleCtaSection,
   CtaPart,
   CommerceUs,
   CategoriesWithSplitImages,
   CategoriesWithScrollingCards,
   CategoriesWithImageBackgrounds,
   ProductListTallImages
 },
  head() {
    return {
      title: 'خیریه مینو',
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content: 'خیریه مینو کمکی برای معلولان'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>
