<template>
  <div>
    <about-me msg="test1"></about-me>
    <button @click="msg += 1">{{computedMsg}}</button>
  </div>
</template>

<script>
import AboutMe from './AboutMe.vue'

export default {
  components: { AboutMe },
  data: function() {
    return {
      msg : 1
    }
  },
  computed:{
      computedMsg: function(){
        return (this.msg % 2) * 10;
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
