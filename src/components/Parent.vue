<template>
<h1>The Parent Section</h1>
<Child name="Sabir khan" :detail="user" :parentFunction="getFun" />
    
</template>

<script>
import Child from './Child.vue'
export default {
    parent: 'Parent',
    components:{
        Child
    },
    data(){
        return{
            user:{
            school:'gcl',
            email:'toplinks56@gmail.com'
            }
        }
    },
    methods:{
        getFun(){
            console.log("the parent function")
            alert("this is sabir function")
        }
    }
}
</script>