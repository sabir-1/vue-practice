<template>
<h2>Two way binding</h2>
<input type="text" v-model="count" />
<h3>{{count}}</h3>
</template>

<script>
export default{
    binding:'Two_Way_Binding',
    data()
    {
        return{
            count:10
        }
    }
}
</script>