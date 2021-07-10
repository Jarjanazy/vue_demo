<template>
  <div>
    <about-me msg="test1"></about-me>
    <button @click="increaseMsg">{{computedMsg}}</button>
    <h2>pressed {{msg}} times</h2>
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
  },
  methods:{
    increaseMsg: function(){
      this.msg += 1;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
