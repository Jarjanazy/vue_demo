<template>
    <div>
      <input type="text" placeholder="Suggest changes" @input="emitText">
    </div>
</template>

<script>
export default {
    name:"about-me",
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
