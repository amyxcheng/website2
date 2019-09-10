<template>
  <div class="home">
    <Intro />
    <Section backgroundColor="white">
      About Me
    </Section>
    <Section class="projects" :backgroundURL="images.spiritIsland">
      Projects
    </Section>
    <Section backgroundColor="white">
      Discover
    </Section>
    <Section class="contact-me" :backgroundURL="images.meadow">
      Contact Me
    </Section>
  </div>
</template>

<script>
// @ is an alias to /src
import Section from "@/components/Section.vue";
import Intro from "@/components/Intro.vue";

// Import images from 'assets' folder.
import emeraldLake from "@/assets/emeraldLake2.jpg";
import morraineLake from "@/assets/morraineLake.jpg";
import me from "@/assets/Me.jpg";
import spiritIsland from "@/assets/spiritIsland.jpg";
import waterfallMe from "@/assets/waterfallMe.jpg";
import meadow from "@/assets/meadow.jpg";

const images = {
  emeraldLake,
  morraineLake,
  me,
  spiritIsland,
  waterfallMe,
  meadow
};

export default {
  data: () => ({
    // Make 'images' variable available to the <template>.
    images
  }),
  components: {
    Section,
    Intro
  }
};
</script>

<style lang="scss" scoped>
.section {
  &.projects,
  &.contact-me {
    background-position: center;
  }
}
</style>
