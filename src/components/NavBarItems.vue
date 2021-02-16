<template>
  <b-navbar fixed="top" class="flex-row">
    <b-navbar-brand><span class="name color-one">IAN</span><span class="name color-two">KRIEGER</span></b-navbar-brand>
    <b-navbar-nav class="ml-auto">
      <b-nav-item @click="$bvModal.show('about-modal')">About</b-nav-item>
      <b-nav-item @click="$bvModal.show('work-modal')">Work</b-nav-item>
      <b-nav-item @click="$bvModal.show('skills-modal')">Skills</b-nav-item>
      <b-nav-item @click="$bvModal.show('contact-modal')">Contact</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>
export default {
  name: "NavBarItems"
}
</script>

<style scoped>

</style>