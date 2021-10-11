<template>
  <div id="app">
      <TheNavigation/>
      <router-view/>
  </div>
</template>

<script>
import TheNavigation from "@/components/TheNavigation";
export default {
  name: "Nav",
  components: {TheNavigation}
}
</script>

