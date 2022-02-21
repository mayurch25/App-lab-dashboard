<template>
  <div class="home">
    <AppHeader></AppHeader>
    <MainSection></MainSection>
    <PartnersLogo></PartnersLogo>
    <FeatureSection></FeatureSection>
    <AppFooter></AppFooter>
  </div>
</template>

<script>

import AppHeader from "../components/AppHeader/Appheader.vue";
import MainSection from "../components/MainSection/mainsection.vue";
import PartnersLogo from "../components/PartnersLogo/partnerslogo.vue";
import FeatureSection from "../components/FeatureApp/feature-section.vue";
import AppFooter from "../components/AppFooter/AppFooter.vue";
export default {
  name: "Home",
  components: {
    AppHeader,
    MainSection,
    PartnersLogo,
    FeatureSection,
    AppFooter
  },
};
</script>
