<template>
  <Section class="projects" :backgroundURL="spiritIsland">
    <h1 class="title">
      Projects.
    </h1>
  </Section>
</template>

<script>
import Section from "@/components/Section.vue";
import spiritIsland from "@/assets/spiritIsland.jpg";

export default {
  data: () => ({ spiritIsland }),
  components: {
    Section
  }
};
</script>

<style lang="scss" scoped>
// @import "@/styles/breakpoints.scss";

.title {
  font-size: 28pt;
  color: white;
  margin-top: 10%;
}
</style>
