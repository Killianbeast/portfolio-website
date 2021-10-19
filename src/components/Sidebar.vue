<template>
    <div class="sidebar">
        <a href="#AboutMe">About Me</a>
        <a href="#Projects">Projects</a>
        <a href="#">Resume</a>
        <a href="#">Contact Me</a>
    </div>
</template>

<script>
export default {
    name: "SideBar",
}
</script>

<style scoped>
.sidenav { 
    width: 150px;
    position: fixed;
    z-index: 1;
    right: 0;
    background-color: black;
    overflow-x: hidden;
}
.sidenav a {
    padding: 6px 8px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
}
.sidenav a:hover {
    color:whitesmoke;
}
</style>