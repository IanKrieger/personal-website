<template>
  <b-modal id="skills-modal" size="xl" scrollable hide-footer centered>
  <template #modal-title>
    SKILLS
  </template>
    <div class=horizontal-lists>
      <div>
        <h6><em>Backend</em></h6>
        <ul>
          <li>Typescript</li>
          <li>Node.js</li>
          <li>GoLang</li>
          <li>Javascript</li>
          <li>Java</li>
          <li>Springboot</li>
          <li>Mockito</li>
          <li>Testify</li>
        </ul>
      </div>
      <div>
        <h6><em>Frontend</em></h6>
        <ul>
          <li>React</li>
          <li>React Query</li>
          <li>Material UI</li>
          <li>Vue</li>
          <li>Jest</li>
        </ul>
      </div>
      <div>
        <h6><em>Infrastructure</em></h6>
        <ul>
          <li>Terraform</li>
          <li>AWS</li>
          <li>SQL (RDS, postgres)</li>
          <li>NoSql (Dynamo)</li>
          <li>Docker</li>
          <li>Git</li>
          <li>Gitlab</li>
          <li>Github</li>
          <li>Kafka</li>
        </ul>
      </div>
      <div>
        <h6><em>Conceptual</em></h6>
        <ul>
          <li>OOP</li>
          <li>CI/CD</li>
          <li>System Design</li>
          <li>Serverless Architecture</li>
          <li>Microservice Architecture</li>
          <li>Event Driven Architecture</li>
          <li>REST / HTTP API Design</li>
          <li>Agile</li>
          <li>Scrum</li>
          <li>Kanban</li>
          <li>Jira</li>
          <li>Confluence</li>
          <li>Postman</li>
          <li>Lucid</li>
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