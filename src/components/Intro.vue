<template>
  <Section class="intro" :backgroundURL="inkPots">
    <h1 class="title">
      Amy Cheng.
    </h1>
  </Section>
</template>

<script>
import Section from "@/components/Section.vue";
import inkPots from "@/assets/inkPots.jpg";

export default {
  data: () => ({ inkPots }),
  components: {
    Section
  }
};
</script>

<style lang="scss" scoped>
.intro {
  color: white;
}

.title {
  font-size: 28pt;
}
</style>
