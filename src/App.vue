<template>
<div id="app">
  <router-view />
</div>
</template>

<style lang="scss">
// Import Bulma's core
@import "~bulma/sass/utilities/_all";

// Set your colors
$kulap: #29419B;
$kulap-invert: findColorInvert($kulap);
$pink: #FFC7C9;
$pink-invert: findColorInvert($pink);
// Setup $colors to use as bulma classes (e.g. 'is-twitter')
$colors: ("white": ($white, $black),
  "black": ($black, $white),
  "light": ($light, $light-invert),
  "dark": ($dark, $dark-invert),
  "primary": ($primary, $primary-invert),
  "info": ($info, $info-invert),
  "success": ($success, $success-invert),
  "warning": ($warning, $warning-invert),
  "danger": ($danger, $danger-invert),
  "kulap": ($kulap, $kulap-invert),
  "pink": ($pink, $pink-invert));

// Import Bulma and Buefy styles
@import "~bulma";
@import "~buefy/src/scss/buefy";

#app,
html,
body {
  font-family: 'Roboto', sans-serif;
  font-style: normal;
  color: #29419B;
}
</style>
