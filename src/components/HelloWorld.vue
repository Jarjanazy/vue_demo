<template>
  <div>
    <about-me></about-me>
    <button>{{msg}}</button>
    <input v-model="msg">
  </div>
</template>

<script>
import AboutMe from './AboutMe.vue'

export default {
  components: { AboutMe },
  data(){
    return {
      msg : "hey"
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
