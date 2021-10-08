<template>
    <div>
    <h1>Name {{getName().name}} </h1>
    <h2>Email {{getName().email}} </h2>
    </div>
</template>

<script>
export default {
    mf:"Methods",
    data(){
        return{
            emailss:"dfjhdkja@gmail.com",
        }
    },
    methods:{
        getName()
        {
        return{
            name:"Khan",
            email: this.emailss,
        }
    }
    }
}
</script>