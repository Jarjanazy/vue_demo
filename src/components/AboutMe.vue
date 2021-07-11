<template>
    <div>
        <button @click="$emit('clicked')">Press me!!</button>
    </div>
</template>

<script>
export default {
    name:"about-me",
    data : function(){
        return{
            
        }  
    }
}
</script>
