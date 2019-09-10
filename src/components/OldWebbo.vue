<template>
  <div class="old-webbo">
    <div class="section" id="title">
      <div class="name">
        <h1>Amy Cheng</h1>

        <h2>UWaterloo Computer Science || WLU Business Administration</h2>
      </div>
    </div>

    <ul>
      <li>
        <a href="#title">Amy Cheng</a>
      </li>
      <li>
        <a href="#about-me">About Me</a>
      </li>
      <li>
        <a href="#projects">Projects</a>
      </li>
      <li>
        <a href="#contact">Connect</a>
      </li>
    </ul>

    <main>
      <div class="section" id="about-me">
        <!--  <img src="pix/me.jpg" id="mepic"> -->
        <div class="section-inner">
          <h1>About Me</h1>
          <p>
            Hi, I'm Amy; welcome to my website! I am currently a second year
            double degree student studying Computer Science at the University of
            Waterloo, and Business Administration at Wilfrid Laurier University.
            I am an eager learner and lover of creating new things.<br />
            I originally intended to create this website and use it as a
            platform for showcasing some of the projects I've worked on.
            However, I would also like to use this site as a place for me to
            express myself beyond the projects and boasting of relevant work
            experiences in attempts to attract job recruiters. Whether it is
            through words, pictures, art, or code, my goal is to be able to
            create a sort of public, creative diary (such as with social media,
            but without the FOMO feeling that comes with scrolling through
            endless amounts of perfectly edited photos posted by friends and
            strangers alike). <br />
            This website was created using HTML/CSS and Javascript after taking
            introductory online courses for those languages. It is hosted
            through my
            <a href="https://github.com/amyxcheng">Github</a>.
          </p>

          <h2>Hobbies and Interests</h2>
          <p>
            In my spare time, I love playing sports! Some of my favourite
            include soccer, figure skating, nordic skiing, and badminton, but
            there are few sports I haven't tried. I am currently learning Muay
            Thai, Dragon Boating, and playing intramural soccer at
            university.<br />
            I also love being outdoors and surrounded by nature. Watching
            sunsets and sunrises, climbing mountains, looking for shooting
            stars, swimming in rivers and oceans, and sitting by a warm fire are
            just a few things that make me immeasurably happy.
          </p>
          <h2>Fun Facts</h2>
          <p>I can ride a unicycle (...more or less).</p>

          <h2><a href="">See my Resume</a></h2>
        </div>
      </div>

      <div class="section" id="projects">
        <div class="section-inner">
          <h1>Projects</h1>
          <p>
            What's a side project?.. Come back later when I've figured that out.
          </p>
          <h2></h2>
        </div>
      </div>

      <div class="section" id="blog">
        <div class="section-inner">
          <h1>Discover</h1>
          <p>Come back soon for more amazingness!</p>
        </div>
      </div>

      <div class="section" id="contact">
        <div class="section-inner">
          <h1>Contact Me</h1>
          <p>
            Thanks for visiting my website! Feel free to contact me through the
            links below. Have a lovely day!
          </p>
          <div class="contact-links">
            <a class="links" href="https://github.com/amyxcheng">Github</a
            ><br />
            <a class="links" href="https://www.linkedin.com/in/amy-c-973192126/"
              >LinkedIn</a
            ><br />
            <a class="links" href="https://www.instagram.com/amycheng99/"
              >Instagram</a
            ><br />
            <a class="links" href="mailto:chengamy99@gmail.com">Email</a>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<style scoped>
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Lato";
}

.section {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;

  width: 100vw;
  height: 100vh;
  box-sizing: border-box;

  background: no-repeat fixed center;
  background-size: cover;
}

/* Title page */

#title {
  /* background-image: url("pix/mountain.jpg"); */
  min-height: 100vh;
}

#title .name {
  height: 250px;
  width: 425px;
  color: white;
  border: 7px white solid;
  padding: 15px;
  text-align: center;
  font-size: x-large;
}

/* Navigation bar at the top*/

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: rgba(0, 0, 0, 0.75);
  position: -webkit-sticky;
  /*Safari*/
  position: sticky;
  top: 0;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 14pt;
  font-weight: bolder;
}

li a:hover {
  background-color: rgba(110, 100, 194, 0.6);
}

/* The About me Section */

#about-me {
  background-color: #7986cb;
  color: white;
  font-size: 20px;
  box-sizing: border-box;
}

.section-inner {
  width: 85vw;
  margin: 0 auto;
  min-width: 200px;
}

#mepic {
  float: left;
  width: 30%;
  margin-left: 10px;
}

#projects {
  color: white;
  padding: 15px;
  font-size: 25px;
  /* min-height: 400px; */
  /* background-image: url("pix/sunset.jpg"); */
}

#blog {
  background-color: #7986cb;
  color: white;
  padding: 15px;
  font-size: 25px;
}

#contact {
  min-height: 100vh;
  color: white;
  padding: 15px;
  font-size: 25px;
  /* min-height: 400px; */
  background-image: url("~/assets/bay.jpg");
  text-align: center;
}

.contact-links {
  border: solid medium white;
  width: 250px;
  text-align: center;
  margin: auto;
  background-color: rgba(255, 255, 255, 0.5);
  color: white;
  text-underline: none;
  padding: 20px;
}

a.links {
  text-decoration: none;
  color: #7986cb;
  font-size: 35px;
}
a.links:link {
}

a.links:visited {
  color: #3f51b5;
}

a.links:hover {
  color: #5c6bc0;
}

a.links:active {
}
</style>
