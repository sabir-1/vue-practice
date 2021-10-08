<template>
<br>
<button v-on:click="getData()">Increments</button>
<button v-on:click="getDerment()">Decrements</button>
<h3>{{count}}</h3>
</template>
<script>
export default{
    event:'Event',
    data(){
        return {
            count:0
        }
    },
    methods:{
        getData()
        {
                this.count=this.count+1;
        },
        getDerment()
        {
                this.count=this.count-1;
        }
    }

}
</script>