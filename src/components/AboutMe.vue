<template>
  <Section class="about-me" background-color="white">
    <div class="content">
      <img class="portrait" src="@/assets/portrait.jpg" />

      <div class="info">
        <h1>About Me</h1>
        <p>
          Hi, I'm Amy; welcome to my website! I am currently a third year double
          degree student studying Computer Science at the University of
          Waterloo, and Business Administration at Wilfrid Laurier University. I
          am an eager learner and lover of creating new things.<br />
          This website is intended to be used as a platform for showcasing some
          of the projects I've worked on. In the future, I might also like to
          use this site as a place for me to express myself creatively (such as
          with social media, but without the FOMO feeling that comes with
          scrolling through endless amounts of perfectly edited photos posted by
          friends and strangers alike). <br />
          This website was originally created using HTML/CSS and Javascript
          after taking introductory online courses for those languages. It now
          also uses the web framework, Vue, to help keep this site organized and
          easily maintained. This site is hosted through my
          <a href="https://github.com/amyxcheng">Github</a>.
        </p>

        <h2>Hobbies and Interests</h2>
        <p>
          In my spare time, I love playing sports! Some of my favourite include
          soccer, figure skating, nordic skiing, and badminton, but there are
          few sports I haven't tried. I am currently learning Muay Thai,
          bouldering, and playing intramural soccer and ultimate frisbee at
          university.<br />
          I also love being outdoors and surrounded by nature. Watching sunsets
          and sunrises, climbing mountains, looking for shooting stars, swimming
          in rivers and oceans, and sitting by a warm fire are just a few things
          that make me immeasurably happy.
        </p>
        <h2>Fun Facts</h2>
        <p>I can ride a unicycle!</p>

        <h2>See my Resume</h2>
      </div>
    </div>
  </Section>
</template>

<script>
import Section from "@/components/Section.vue";

export default {
  components: {
    Section // register Section for use in the <template />
  }
};
</script>

<style lang="scss" scoped>
.about-me {
  box-sizing: border-box;
}

.content {
  display: flex;
  padding: 30px;
  max-width: 900px;
  font-size: 18px;
}

.portrait {
  margin: 160px -20px 0 0;
  position: relative;
  right: 100px;

  width: 200px;
  height: 225px;
  border-radius: 5px;
  object-fit: cover;
  object-position: left;
  /* margin-left: auto;
  margin-right: auto;
  margin-top: 100px; */
  /* float: left; */
}
</style>
