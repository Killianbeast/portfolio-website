<template>
  <Header title="Home Page"/>
  <SideBar class="sidenav"/>
  
  <div id="AboutMe">
    <h1>About Me</h1>
  </div>

  <div id="Projects">
    <h1>Projects</h1>
  </div>

  <div id="Resume">
    <h1>Resume</h1>
  </div>

  <div id="Contact">
    <h1>Contact Me</h1>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import SideBar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Header,
    SideBar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@200&display=swap');
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Roboto Mono', monospace;
}
</style>

