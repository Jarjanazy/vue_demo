<template>
<div>
  <div>
    <h2>SUP {{name}}</h2>
    <button v-bind:disabled="isHere"> Click </button>
  </div>

  <div>
    <h2 v-for="(car, index) in cars" :key="index">
      {{car}}
    </h2>
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return {
      name : "abdo",
      isHere : false,
      cars : ["toyota", "jaaag"]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
