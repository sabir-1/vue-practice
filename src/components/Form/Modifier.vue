<template>
<h1>The Modifier</h1>
    <input type="number" v-model="data" />
    <h3>The Data is : {{typeof(data)}}</h3>
</template>
<script>
export default {
  Mod: 'Modifier',
  data(){
      return{
          data:""
      }
  }
}
</script>