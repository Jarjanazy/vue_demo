<template>
  <div>
    <about-me v-model="msg"/>
    <h2> {{msg}} </h2>
  </div>
</template>

<script>
import AboutMe from './AboutMe.vue'

export default {
  components: { AboutMe },
  data: function() {
    return {
      msg: "hey"
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
