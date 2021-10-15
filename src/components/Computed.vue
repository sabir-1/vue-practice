<template>
    <h1>Compute Properity</h1>
    <h3>{{getResult}}</h3>
</template>
<script>
export default {
    com: "Computed",
    data(){
        return{
            dollar: 100,
            pakValue:50,
            discount:100
        }
    },
    computed:{
        getResult(){
            return (this.dollar*this.pakValue)-this.discount;
        }

    }
}
</script>