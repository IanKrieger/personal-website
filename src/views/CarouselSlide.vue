<template>
  <div>
    <b-carousel
        id="carousel-1"
        :interval="0"
        v-model="slide"
        controls
        fade
        indicators
        background="#ababab"
        style="text-shadow: 1px 1px 2px #333;"
    >
      <b-carousel-slide
          img-src="https://picsum.photos/id/307/1024/500?grayscale"
      >
        <h3 class="carousel-caption" @click="$bvModal.show('about-modal')">About</h3>
      </b-carousel-slide>
      <b-carousel-slide
          img-src="https://picsum.photos/id/536/1024/500?grayscale"
      >
        <h3 class="carousel-caption" @click="$bvModal.show('work-modal')">Work</h3>
      </b-carousel-slide>
      <b-carousel-slide
          img-src="https://picsum.photos/id/499/1024/500?grayscale"
      >
        <h3 class="carousel-caption" @click="$bvModal.show('skills-modal')">Skills</h3>
      </b-carousel-slide>
      <b-carousel-slide
          img-src="https://picsum.photos/id/184/1024/500?grayscale"
      >
        <h3 class="carousel-caption" @click="$bvModal.show('contact-modal')">Contact</h3>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: "CarouselSlide",
  props: {
    slide: {
      value: 0
    }
  }
}
</script>

<style scoped>
h3:hover {
  cursor: pointer;
}
</style>