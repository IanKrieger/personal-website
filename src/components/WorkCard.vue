<template>
  <b-modal id="work-modal" size="xl" scrollable hide-footer centered>
    <template #modal-title>
      WORK
    </template>
    <div class="d-block text-left">
      <div class="d-inline-block">
        <p class="d-md-inline">
          Enthusiastic and fast learning software engineer with 5+ years of coding experience.
          Have worked on a multitude of projects in a variety of languages ranging from enhancements on large complex code bases to participating in the complete project development life cycle of successfully launched applications.
          Effective communicator and advocate for healthy Software Engineering cultures and work related practices.
        </p>
        <div class="d-md-inline">
          <h6 class="modal-header">Circulo Health - Senior Software Engineer <small><em>May 2021 - Present</em></small></h6>
          <p class="text-body">
            At Circulo I am a Senior Software Engineer mostly focused on the backend, however I have delivered a few front end projects as well.
            I have done quite a lot during my time at Circulo, and have mostly been focused on developing communication related functionality for a few different products.
            I primarily develop using Typescript, Golang and React. I have built everything from simple internal API's to a full fledged event driven service meant for effective message delivery.
            I have also built many production ready proof of concepts.
          </p>
        </div>
        <div class="d-md-inline">
          <h6 class="modal-header">Updox, LLC - Software Engineer <small><em>Aug 2019 - May 2021</em></small></h6>
          <p class="text-body">
            At Updox, I have worked on almost everything. I started off writing EHR integrations utilizing Kafka, Kotlin
            & SpringBoot.
            I then moved onto adding additional integrations for clients that used windows integrations in C#.
            Then, I started to improve and enhance our communications suite. Which used a mix of AngularJs, Java,
            Kotlin, React.
            After that I moved to help the L3 support team. Diagnosing production issues and funneling work to the
            correct teams.
            After that, I started a greenfield Form delivery application. That used a mix of Java, Spring, and VueJs.
            I also worked on the core product, delivering critical bug fixes and enhancements using
            AngularJs and Java.
          </p>
        </div>
        <div class="d-md-inline">
          <h6 class="modal-header">JP Morgan Chase - Software Engineer <small><em>July 2017 - Aug 2019</em></small></h6>
          <p class="text-body">
            At Chase, I was a back-end software engineer working in the transaction processing area.
            That is the place that all your checks go through. It was a large scale 24/7 environment and very critical
            to the bank.
            I automated their deploys, helped transition them from SVN to GIT, and helped mentor new college aged
            software engineers.
            In my day job, I wrote back-end Java REST based & event-driven microservices that utilized SpringBoot,
            Kafka, UMQ, REST, Cassandra, and Maven.
            I worked there for a little over 2 years.
          </p>
        </div>
      </div>
    </div>
  </b-modal>
</template>

<script>
export default {
  name: "WorkCard"
}
</script>

<style scoped>

</style>