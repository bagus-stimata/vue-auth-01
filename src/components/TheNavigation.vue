<template>
  <div>
    <ul>
      <li>
        <router-link
            :to="{ name: 'Home' }">Home</router-link>
      </li>
      <li>
        <router-link  :to="{ name: 'dashboard' }">Dashboard</router-link>
      </li>
      <li>
        <router-link  to="/signin">Sign In</router-link>
      </li>
      <li>Bagus Winarno</li>
      <li>
        <a href="#">Sign Out</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "TheNavigation",
}
</script>

<style scoped>

</style>