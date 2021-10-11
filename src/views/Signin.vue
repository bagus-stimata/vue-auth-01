<template>
  <div>
    <h1>Signin</h1>
    <form @submit.prevent="submit">
      {{ form }}
      <div>
        <label for="email">Email</label>
        <input type="text" name="email" id="email" v-model="form.email" />
      </div>
      <div>
        <label for="password">Password</label>
        <input type="text" name="password" id="password" v-model="form.password"/>
      </div>
      <div>
        <button type="submit">Sign In</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "Signin",
  data() {
    return {
      form :{
        email: '',
        password: ''
      }
    }
  },
  methods: {
    submit() {

    }
  }

}
</script>

<style scoped>

</style>