<template>
  <div class="flex">
    <nav-bar-items />
    <carousel-slide />
    <about-me-card />
    <contact-card />
    <skills-card />
    <work-card />
    <help-side-bar />
  </div>
</template>

<script>

import CarouselSlide from "@/views/CarouselSlide";
import NavBarItems from "@/components/NavBarItems";
import AboutMeCard from "@/components/AboutMeCard";
import ContactCard from "@/components/ContactCard";
import SkillsCard from "@/components/SkillsCard";
import WorkCard from "@/components/WorkCard";
import HelpSideBar from "@/components/HelpSideBar";
export default {
  name: 'App',
  components: {HelpSideBar, WorkCard, SkillsCard, ContactCard, AboutMeCard, NavBarItems, CarouselSlide},
  mounted() {
    document.getElementsByTagName("img").forEach(item => {
      item.style["height"] = `${window.innerHeight}px`;
      item.style["width"] = `${window.innerWidth}px`;
    });

    window.addEventListener('resize', function() {
      document.getElementsByTagName("img").forEach(item => {
        item.style["height"] = `${window.innerHeight}px`;
        item.style["width"] = `${window.innerWidth}px`;
      });
    });
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.name {
  font-family: Verdana,monospace;
  font-size: 40px;
  font-weight: 400;
  letter-spacing: .5em;
}

@media only screen and (max-width: 867px)  {
  .name {
    font-family: Verdana,monospace;
    font-size: 30px;
    font-weight: 400;
    letter-spacing: .25em;
  }
}

.navbar-nav {
  justify-content: right !important;
  flex-grow: 1 !important;
}

.color-one {
  color: lightgray;
}

.color-two {
  color: indianred;
}

a {
  color: lightgrey !important;
  font-family: Verdana,monospace !important;
  font-size: 18px !important;
}

.lightgrey {
  color: lightgrey;
  font-family: Verdana,monospace;
}

.flex {
  display: flex;
  flex-direction: column;
}

.flex-row {
  display: flex;
  flex-wrap: wrap !important;
}

.modal-content {
  background-color: grey !important;
  opacity: .8 !important;
}
</style>
