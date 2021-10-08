<template>
<div class="parent-sec">
    <p>{{preData.name}} </p>
    <p><b>{{preData.email}}</b></p>
    <button v-on:click="getdata(preData.name)" > Click </button>
</div>
</template>

<script>
export default {
    Parent: "ParentComp",
    props: {
        preData: Object,
        getdata:Function
    }
    
}
</script>

<style>
.parent-sec {
    background: #41b883;
    padding: 6px 8px;
    margin: 10px 0;
    color: #fff;
}
</style>
