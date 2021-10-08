<template>
<h1>The Child Function {{name}}</h1>
<h3>{{detail.school}} <span>{{detail.email}}</span></h3>
<button v-on:click="parentFunction()" >click</button>
    
</template>

<script>
export default {
    child:"Child",
    props:{
        name:String,
        detail:Object,
        parentFunction:Function
    }
}
</script>