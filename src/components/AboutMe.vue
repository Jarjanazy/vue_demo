<template>
    <div>
      <input type="text" placeholder="Suggest changes" @input="emitText">
      <h3>{{value}}</h3>
    </div>
</template>

<script>
export default {
    name:"about-me",
    props: {
        value: {type : String}
    },
    data : function(){
        return{}  
    },
    methods: {
        emitText : function(e){
            this.$emit('input', e.target.value);
        }
    }
}
</script>
