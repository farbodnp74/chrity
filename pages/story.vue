<template>
  <div>
    <NuxtLayout name="custom">
      <with_fading_image/>
      <With_split_image/>
      <ThePart2Component/>

    </NuxtLayout>
  </div>

</template>

<script>
import With_split_image from "../components/with_split_image";
import With_fading_image from "../components/with_fading_image";
import ThePart2Component from "../components/ThePart2Component.vue";
export default {
  name: "story",
  components: {ThePart2Component, With_fading_image, With_split_image}
}
</script>

<style scoped>

</style>
