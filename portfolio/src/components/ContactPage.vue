<template>
  <div>
    <h2>Contact</h2>
    <form>
      <label>
        Name:
        <input type="text" v-model="name" />
      </label>
      <br />
      <label>
        Email:
        <input type="email" v-model="email" />
      </label>
      <br />
      <label>
        Message:
        <textarea v-model="message"></textarea>
      </label>
      <br />
      <button @click="submitForm">Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: '',
      email: '',
      message: ''
    }
  },
  methods: {
    submitForm() {
      // handle form submission, for example, send data to a server using an HTTP client library
      // you can use axios or fetch to handle the post request
      console.log(this.name, this.email, this.message)
    }
  }
}
</script>

