<template>
  <div>
    <input v-model="text">
    <about-me :msg="text"></about-me>
    <about-me :msg="text"></about-me>
  </div>
</template>

<script>
import AboutMe from './AboutMe.vue'

export default {
  components: { AboutMe },
  data: function() {
    return {
      text : "Write here"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
