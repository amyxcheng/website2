<template>
  <div id="app">
    <!-- the line below will appear on all pages of the site -->
    <!-- <h1>yo wassup its amy</h1> -->

    <!-- show page contents -->
    <router-view />
  </div>
</template>

<style lang="scss">
// Styles that affect the entire website.

body {
  font-family: Lato, "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  margin: 0;
  background: lavender;
}

// prettier-ignore
h1, h2, h3, h4, h5, h6 {
  font-family: "Playfair Display", serif;
  &p { margin: 0; }
}
</style>
