<template>
  <div>
    <button>{{msg}}</button>
    <input v-model="msg">
  </div>
</template>

<script>
export default {
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
