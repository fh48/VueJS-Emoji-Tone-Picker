<template>
  <div id="app">
    <header>
      <img src="./assets/logo.png" alt="Vue.js PWA">
      <span>PVA Tutorials - VueJS Emoji Tone Picker</span>
    </header>
    <!-- <h1>Build a Emoji Tone Selector</h1> -->
    <toneSelector selectedEmoji="&#x1F64F;"/>
  </div>
</template>

<script>
import toneSelector from "./components/toneSelector";

export default {
  name: "App",
  components: {
    toneSelector
  }
};
</script>

<style>
html body {
  margin: 0px;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

header {
  margin: 0;
  height: 56px;
  padding: 0 16px 0 24px;

  background-color: #35495e;
  color: #ffffff;
  display: flex;
  align-items: center;
}

header img {
  height: 30px;
}

header span {
  display: block;
  position: relative;
  font-size: 20px;
  line-height: 1;
  letter-spacing: 0.02em;
  font-weight: 400;
  box-sizing: border-box;
  padding-left: 10px;
}
</style>
