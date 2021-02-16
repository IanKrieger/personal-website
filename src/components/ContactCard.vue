<template>
  <b-modal id="contact-modal" size="xl" scrollable hide-footer
           @show="onReset"
           @hidden="onReset"
           centered
  >
    <template #modal-title>
      CONTACT
    </template>
    <b-form @submit.prevent="onSubmit" @reset.prevent="onReset">
      <b-form-group
          id="input-group-1"
          label="Name"
          label-for="input-1"
      >
        <b-form-input
            id="input-1"
            v-model.trim="form.name"
            type="text"
            placeholder="Enter Name"
            required
        ></b-form-input>
      </b-form-group>
      <b-form-group
          id="input-group-2"
          label="Email address:"
          label-for="input-2"
      >
        <b-form-input
            id="input-2"
            v-model.trim="form.email"
            type="email"
            placeholder="Enter email"
            required
        ></b-form-input>
      </b-form-group>
      <b-form-group
          id="input-group-3"
          label="Message"
          label-for="input-3"
      >
        <b-form-input
            id="input-3"
            v-model.trim="form.message"
            type="text"
            placeholder="Enter Message..."
            required
        ></b-form-input>
      </b-form-group>

      <b-button type="submit" class="margin" variant="dark" :disabled="submitting">Submit</b-button>
      <b-button type="reset" variant="outline-dark">Reset</b-button>
    </b-form>
  </b-modal>
</template>

<script>
import axios from 'axios';

export default {
  name: "ContactCard",
  data: () => ({
    form: {
      name: "",
      email: "",
      message: ""
    },
    submitting: false
  }),
  methods: {
    onReset() {
      this.form.name = ""
      this.form.email = ""
      this.form.message = ""
    },
    onSubmit() {
      this.submitting = true;
      axios.post("https://getform.io/f/bdf3a892-2c15-4bd8-802d-09a46a9df250", this.form)
      this.onReset()
      this.submitting = false;
    }
  },
  computed: {}
}
</script>

<style scoped>
.margin {
  margin-right: 10px;
}
</style>