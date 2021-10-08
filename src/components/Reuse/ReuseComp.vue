<template>
<h2>The ReuseComp</h2>

<ul>
    <li v-for="item in user " :key="item.name">
        
        <ParentComp :preData="item" :getdata="getdata" /> 
    </li>
</ul>
    
</template>

<script>

import ParentComp from './ParentComp.vue';

export default {
    Reuse:"ReuseComp",
    components:{
        ParentComp,
    },
     methods:{
        getdata(name){
            alert(name)
        }
    },
   
    data(){
        return{
            user:[
                {
                    name:'john',
                    email:'john@gmail.com'
                },
                {
                    name:'peter',
                    email:'peter@gmail.com'
                },
                {
                    name:'justin',
                    email:'justin@gmail.com'
                },
                {
                    name:'ada',
                    email:'ada@gmail.com'
                },
            ]
        }
    }
}
</script>