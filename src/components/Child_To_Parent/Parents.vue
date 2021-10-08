<template>
    <h1>The Parents {{childUser}}</h1>
    <Child :fetchUser="getUser" />
</template>

<script>
import Child from './Child.vue'
export default {
    name:"Parents",
    data(){
        return{
            childUser:""
        }
    },
    components:{
        Child
    },
    methods:{
        getUser(name){
           this.childUser=name
        }
    }
    
}
</script>