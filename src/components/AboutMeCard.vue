<template>
  <b-modal id="about-modal" size="xl" scrollable hide-footer centered>
    <template #modal-title>
      ABOUT ME
    </template>
    <div class="d-block text-left">
      <div class="d-md-inline-block">
        <h6 class="modal-header">Hometown and Current Location</h6>
        <p class="text-body">
          I grew up in a suburb near Cleveland Ohio, where I lived for the majority of my life.
          I now live in Dayton, Ohio. I recently moved there from Columbus, OH.
          In Columbus I worked at J.P Morgan Chase as a back-end software engineer.
          I also worked at Updox as a full stack engineer.
          I currently work at Circulo Health remotely in Dayton as a Senior Software Engineer.
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
          One of the things that interests me the most is Serverless Architecture.
          I think any new app could be written to go to the cloud both quickly and securely.
          I also think machine learning is pretty cool, I have actually built a small python script that processes lines of text in a file and then creates it's own original output.
          I am also having a lot of fun with Vue applications, it's a cool JS framework. That's what this is built in!
        </p>
      </div>
      <div>
        <h6 class="modal-header">What I like to do in my free time</h6>
        <p class="text-body">
          Recently a lot of my free time has been taken up by my dog, Hazel. She is an Australian Shepard!
          There are a few cool spots around Dayton that my wife Molly and I enjoy going to.
          Our favorite restaurant is Thai 9, and our favorite Brewery is Eudora.
          The rest of my time is dedicated to projects around the house, which is fun but time consuming!
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