<template>
    <h1>Watchers Properity</h1>
    <h3>{{count}}</h3>
    <button v-on:click="count=count+1">plus</button>
    <button v-on:click="count=count-1">Min</button>
</template>
<script>
export default {
    com: "Watchers",
    data(){
        return{
            count:0
        }
    },
    watch:{
        count(val,pre){
            if(val>5 && val>pre){
                alert("show")
            }
          

        }
    }
    
}
</script>