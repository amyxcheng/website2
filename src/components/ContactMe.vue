<template>
  <Section class="contactMe" :backgroundURL="meadow">
    <div class="contact-me">
      <h1 class="title">
        Contact Me.
      </h1>
      <div class="contact-links">
        <a class="links" href="https://github.com/amyxcheng">Github</a><br />
        <a class="links" href="https://www.linkedin.com/in/amy-c-973192126/"
          >LinkedIn</a
        ><br />
        <a class="links" href="https://www.instagram.com/amycheng99/"
          >Instagram</a
        ><br />
        <a class="links" href="mailto:chengamy99@gmail.com">Email</a>
      </div>
    </div>
  </Section>
</template>

<script>
import Section from "@/components/Section.vue";
import meadow from "@/assets/meadow.jpg";

export default {
  data: () => ({ meadow }),
  components: {
    Section
  }
};
</script>

<style lang="scss" scoped>
// @import "@/styles/breakpoints.scss";

.contact-me {
  padding: 30px;
  max-width: 900px;
  text-align: center;
}

.title {
  font-size: 28pt;
  color: white;
}

.contact-links {
  color: white;
  font-size: 18px;
}
</style>
