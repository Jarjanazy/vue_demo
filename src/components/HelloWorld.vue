<template>
  <div>
    <about-me :msg="msg"/>
    <input type="text" placeholder="enter string" v-model="msg">
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
