<template>
<h1>Components Get Input Value</h1>
<input type="email" placeholder="E-mail" v-model="email" />
<br/>
<input type="password" placeholder="Password" v-model="password"/>
<br/>
<button type="button" v-on:click="getValue">Get Value</button>


    
</template>
<script>
export default {
    get: 'Get_Input_Value',
    data()
    {
        return{
            email:null,
            password:null
        }
    },
    methods:{
        getValue(){
            console.log("Get value",this.email,this.password)
        }
    }
}
</script>
