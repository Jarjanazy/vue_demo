<template>
  <div>
    <about-me v-on:clicked="pressed"></about-me>
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
  },
  methods:{
    pressed : function(){
      alert('stop it!!!!');
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
