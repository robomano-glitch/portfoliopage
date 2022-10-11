<template>
  <div class="home">
    <headerSection />
    <contactSection />
    <techStack />
    <aboutSection />
    <positionSection />
    <repositoriesSection />
  </div>
</template>

<script>
import headerSection from "@/components/headerPage.vue";
import contactSection from "@/components/contactSection.vue";
import aboutSection from "@/components/aboutSection.vue";
import techStack from "@/components/techStack.vue";
import positionSection from "@/components/positionsSection.vue";
import repositoriesSection from "@/components/myRepositories.vue";

export default {
  name: 'Home',
  components: {
    headerSection,
    contactSection,
    aboutSection,
    techStack,
    positionSection,
    repositoriesSection 
  }
}
</script>
