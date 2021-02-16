<template>
  <b-modal id="skills-modal" size="xl" scrollable hide-footer centered>
  <template #modal-title>
    SKILLS
  </template>
    <div class=horizontal-lists>
      <div>
        <h6><em>3 + years</em></h6>
        <ul>
          <li>Java</li>
          <li>SpringBoot</li>
          <li>Maven</li>
          <li>Git</li>
          <li>REST</li>
          <li>HTML5 / CSS</li>
          <li>Junit + Mockito</li>
        </ul>
      </div>
      <div>
        <h6><em>1 - 2 + years</em></h6>
        <ul>
          <li>SQL</li>
          <li>NoSQL</li>
          <li>VueJS</li>
          <li>AngularJS</li>
          <li>Kotlin</li>
          <li>Kafka</li>
          <li>CI/CD (Jenkins)</li>
        </ul>
      </div>
      <div>
        <h6><em>0 - 1 + years</em></h6>
        <ul>
          <li>Python</li>
          <li>AWS</li>
          <li>GraphQL</li>
          <li>Ruby</li>
          <li>ReactJs</li>
        </ul>
      </div>
      <div>
        <h6><em>Soft Skills</em></h6>
        <ul>
          <li>Hard Working</li>
          <li>Efficient Communicator</li>
          <li>Teamwork</li>
          <li>Agile Methodology</li>
          <li>SDLC / OOP</li>
          <li>Time Management</li>
          <li>Startup Experience</li>
        </ul>
      </div>
    </div>
  </b-modal>
</template>

<script>
export default {
  name: "SkillsCard"
}
</script>

<style scoped>
.horizontal-lists {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  flex-wrap: wrap;
}
</style>