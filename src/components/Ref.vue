<template>
    <h2>The Ref {{getData}} </h2>
    <input type="text" ref="input"  value=""/>
    <br>
    <button v-on:click="getVal()">CLick Get Value </button>
</template>

<script>
export default {
    reerence:"Ref",
    data(){
       return{
            getData:""
       }
    },
    methods:{
        getVal(){
            this.$refs.input.focus();
            let va=this.$refs.input.value;
            this.getData=va
        }
    }
}
</script>