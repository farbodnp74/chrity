<template>
  <div>
    <Head>
      <Title>
        درباره مینو
      </Title>
    </Head>
    <NuxtLayout name="custom">

      <ContactUs/>
      <CommerceUs/>
      <TheAdressComponent/>
      <TeamSection/>
    </NuxtLayout>
  </div>
</template>

<script>
import TeamSection from "../components/TeamSection";
import SimpleSlate from "../components/SimpleSlate";
import SimpleFeed from "../components/SimpleFeed";
import ContactUs from "../components/ContactUs";
import CommerceUs from "../components/CommerceUs";
import TheAdressComponent from "../components/TheAdressComponent.vue";
export default {
  name: "about",
  components: {TheAdressComponent, CommerceUs, ContactUs, SimpleFeed, SimpleSlate, TeamSection}
}
</script>

<style scoped>

</style>
