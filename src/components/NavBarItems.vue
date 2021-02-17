<template>
  <b-navbar fixed="top" class="flex-row">
    <b-navbar-brand><span class="name color-one">IAN</span><span class="name color-two">KRIEGER</span></b-navbar-brand>
    <b-navbar-nav class="ml-auto">
      <b-nav-item @click="updateSlide('about-modal', 0)">About</b-nav-item>
      <b-nav-item @click="updateSlide('work-modal', 1)">Work</b-nav-item>
      <b-nav-item @click="updateSlide('skills-modal', 2)">Skills</b-nav-item>
      <b-nav-item @click="updateSlide('contact-modal', 3)">Contact</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>
export default {
  name: "NavBarItems",
  methods: {
    updateSlide(modalName, slideNum) {
      this.$bvModal.show(modalName)
      this.$emit('change-slide', slideNum)
    }
  }
}
</script>

<style scoped>

</style>