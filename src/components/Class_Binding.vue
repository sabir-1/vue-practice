<template>
<h1> The Class Binding</h1>

<h2 class="otherclass" :class="applyStyle"> Change Colors</h2>
<br>
<button v-on:click="colorfull=!colorfull" >Click</button>
    
</template>

<script>
export default {
    classbinfing:'Class_Binding',
    data(){
        return{
            colorfull:true
        }
    },
    computed:{
        applyStyle(){
            return{
                green:this.colorfull,
                light:false,
                fons:true



            }
        }
    }

}
</script>

<style  scoped>

.green{
    background-color: brown;
    width: 400px;
    padding: 10px 4px;
}
.light{
    background-color:cadetblue;
    width: 400px;
    padding: 10px 4px;
    color: white;
}
.fons{
    font-size: 40px;
}

</style>