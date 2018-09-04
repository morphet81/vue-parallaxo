<template>
  <div id="app">
    <!-- <h1>Parallax example</h1> -->

    <parallaxo-background class="parallaxo" src="images/parallax.jpg">

      <h2>This is</h2>

      <h2>An example</h2>

      <h2>Of a</h2>

      <h2>Parallax</h2>

      <h2>Parallax</h2>

    </parallaxo-background>
  </div>
</template>

<script>
import './components'

export default {
  name: 'app',
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  height: 100vh;
  display: flex;
  flex-direction: column;
}

html, body {
  margin: 0;
  padding: 0;
}

.parallaxo {
  flex-grow: 1;

  h2 {
    color: black;
    margin: 20vh 0 0vh 0;
    padding: 12px;
    background-color: rgba(165, 165, 165, 0.377);
  }
}
</style>
