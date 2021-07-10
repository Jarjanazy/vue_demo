<template>
    <h2> {{me}}</h2>
</template>

<script>
export default {
    name:"about-me",
    props: ['msg'],
    data : function(){
        return{
            me : "this is me " + this.msg
        }  
    }
}
</script>
