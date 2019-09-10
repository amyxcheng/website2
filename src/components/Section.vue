<template>
  <div class="section" :style="style">
    <slot />
  </div>
</template>

<script>
// <Section>
// <!-- anything inside here -->
// </Section>

export default {
  // Properties that can be given to an "instance" of a Section.
  props: {
    backgroundColor: {
      type: String,
      default: "lavender"
    },
    backgroundURL: String
  },
  computed: {
    style() {
      // If 'backgroundURL' prop is set...
      if (this.backgroundURL)
        return { backgroundImage: `url(${this.backgroundURL})` };

      // Else, return a style with a background color.
      return { backgroundColor: this.backgroundColor };
    }
  }
};
</script>

<style lang="scss" scoped>
@import "@/styles/breakpoints.scss";

.section {
  width: 100vw;
  height: 100vh;
  box-sizing: border-box;

  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: fixed top/cover no-repeat;

  @include breakpoint(mobileonly) {
    background-attachment: unset;
  }
}
</style>
