<template>
    <h2 v-if="show">if else conditions </h2>
    <h2 v-else>if else conditions 3333 </h2>

    <button v-on:click="show=!show">Click</button>

</template>
<script>
export default {
    condition:'If_Else_Conditions',
    data(){
        return{
            show:false
        }
    }
}
</script>