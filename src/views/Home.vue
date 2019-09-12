<template>
  <div class="home">
    <Intro />
    <AboutMe />
    <Projects />
    <Section backgroundColor="white">
      Discover
    </Section>
    <ContactMe />
  </div>
</template>

<script>
// @ is an alias to /src
import Section from "@/components/Section.vue";
import Intro from "@/components/Intro.vue";
import AboutMe from "@/components/AboutMe.vue";
import Projects from "@/components/Projects.vue";
import ContactMe from "@/components/ContactMe.vue";

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
    Intro,
    AboutMe,
    Projects,
    ContactMe
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
