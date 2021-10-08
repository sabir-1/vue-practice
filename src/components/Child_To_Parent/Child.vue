<template>
    <h2>The Child components</h2>
    <button v-on:click="fetchUser(user)" >Click</button>
</template>

<script>

export default {
    childs:"Child",
    data(){
        return{
            user:"Sabir"
        }
    },
    props:{
        fetchUser:Function
    }

}
</script>