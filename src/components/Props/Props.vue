<template>
    <h1>The Mai Props Data</h1>
    <Students :data="data"/>
    <Teachers :tdata="data"/>
</template>

<script>
import Students from './Students.vue';
import Teachers from './Teachers.vue';
export default {
    wrapProps: 'Props',
    data(){
        return{
            data:"peter"
        }
    },
    components:{
        Students,
        Teachers
    }
}
</script>