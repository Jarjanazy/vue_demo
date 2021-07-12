<template>
    <div>
      <h2>{{msg}}</h2>
    </div>
</template>

<script>
export default {
    name:"about-me",
    props : {
        msg: {type : String}
    },
    data : function(){
        return{
            
        }  
    }
}
</script>
