<template>
  <div>
    <NuxtLayout name="custom">
      <with_fading_image/>
      <With_split_image/>

    </NuxtLayout>
  </div>

</template>

<script>
import With_split_image from "../components/with_split_image";
import With_fading_image from "../components/with_fading_image";
export default {
  name: "story",
  components: {With_fading_image, With_split_image}
}
</script>

<style scoped>

</style>
