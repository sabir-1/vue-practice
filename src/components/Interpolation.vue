<template>

<!-- <h1>This is Interpolation {{"Hello".length}}</h1>   //Interpolation  -->


   <div>
      <h1>Site Name Is {{overAll("Khan")}}</h1>
      <h2>Email {{emails}} </h2>
      <h3>phone {{phone}} </h3>
      <h3>phone {{phone==3453}} </h3>
   </div>

    
</template>

<script>
export default {
   Inter:'Interpolation',
   data()
   {
      return{
         emails:'toplinks56@gmail.com',
         phone:999999,
         overAll:function(a){
            return a
         }
         
      }

   }
}
</script>
