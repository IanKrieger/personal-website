<template>
  <b-modal id="about-modal" size="xl" scrollable hide-footer centered>
    <template #modal-title>
      ABOUT ME
    </template>
    <div class="d-block text-left">
      <div class="d-md-inline-block">
        <h6 class="modal-header">Hometown and Current Location</h6>
        <p class="text-body">
          I grew up in a suburb near Cleveland Ohio, where I lived for the majority of my life. I now live in Columbus, Ohio which is where I have lived for all of my professional life.
          In Columbus I've worked at J.P Morgan Chase as a back-end software engineer.
          I now work at Updox as a full stack engineer. Using a mix of languages to contribute to the overall product.
        </p>
      </div>
      <div>
        <h6 class="modal-header">College</h6>
        <p class="text-body">
          I attended College at The University Of Dayton Where I got my B.S in Computer Information Systems and a minor in Business Administration.
          I also worked in the IT department doing tech support for 3 years of my time there.
        </p>
      </div>
      <div>
        <h6 class="modal-header">What tech I'm passionate about</h6>
        <p class="text-body">I like to make sure I'm up to date on current technology trends.
          One of the things that interests me the most is Machine Learning.
          I have actually built a small python script that processes lines of text in a file and then creates it's own original output.
          I also like AWS for infrastructure, I think any new app could be written to go to the cloud both quickly and securely.
          I am also having a lot of fun with Vue applications, it's a cool JS framework. That's what this is built in!
        </p>
      </div>
      <div>
        <h6 class="modal-header">What I like to do in my free time</h6>
        <p class="text-body">
          Recently a lot of my free time has been taken up by my dog, Hazel. She is an Australian Shepard puppy!
          I like to go to different breweries around Columbus (if you didn't know, there are a lot). My favorite being
          Pretentious Brewing. They make only sour beers, so be prepared!
          I also like to try different restaurants as well! My favorite being Wolfe's Ridge (which also has some of my favorite beers).
          The rest of my time is spent coding or playing video games. Recently I have been playing through Hades. An amazing game!
        </p>
      </div>
    </div>
  </b-modal>
</template>

<script>
export default {
  name: "AboutMeCard"
}
</script>

<style>
</style>