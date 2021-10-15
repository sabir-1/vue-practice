<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <Home data="props data pass" msg="second data pass"/> -->
  <!-- <Interpolation /> -->
  <!-- <Methods/> -->
  <!-- <Event/> -->
  <!-- <Two_Way_Binding/> -->
  <!-- <Get_Input_Value/> -->
  <!-- <Get_Checkbox_Value/> -->
  <!-- <If_Else_Conditions/> -->
  <!-- <For_Loop/> -->
  <!-- <Parent/> -->
  <!-- <ReuseComp/> -->
  <!-- <Html_binding/> -->
  <!-- <Class_Binding/> -->
  <!-- <Props/> -->
  <!-- <Parents/> -->
  <!-- <Ref/> -->
  <!-- <Simple_form/> -->
  <!-- <Modifier/> -->
  <!-- <Computed/> -->
  <!-- <Watchers/> -->
  <!-- <Parent/> -->
  <Cities/>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import Home from './components/Home.vue'
// import Interpolation  from './components/Interpolation.vue'
// import Methods from './components/Methods.vue'
// import Event from './components/Event.vue'
// import Two_Way_Binding from './components/Two_Way_Binding.vue'
// import Get_Input_Value from './components/Get_Input_Value.vue'
// import Get_Checkbox_Value from './components/Get_Checkbox_Value.vue'
// import If_Else_Conditions from './components/If_Else_Conditions.vue'
// import For_Loop from './components/For_Loop.vue'
// import Parent from './components/Parent.vue'
// import ReuseComp from  './components/Reuse/ReuseComp.vue'
// import Html_binding from './components/Html_binding.vue'
// import Class_Binding from './components/Class_Binding.vue'
// import Props from './components/Props/Props.vue'
// import Parents from './components/Child_To_Parent/Parents.vue'
// import Ref from './components/Ref.vue'
// import Simple_form from './components/Form/Simple_form.vue'
// import Modifier from './components/Form/Modifier.vue'
// import Computed from './components/Computed.vue'
// import Watchers from './components/Watchers.vue'
// import Parent from './components/Slots/Parents.vue'
import Cities from './components/Dynamic_Component/Cities.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    // Home,
    // Interpolation, 
    // Methods,
    // Event
    // Two_Way_Binding,
    // Get_Input_Value,
    // Get_Checkbox_Value
    // If_Else_Conditions
    // For_Loop,
    // ReuseComp
    // Html_binding,
    // Class_Binding
    // Props
  //  Ref
  // Simple_form
  // Modifier
  // Computed
  // Watchers
  Cities
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
  max-width: 1180px;
  margin: 0 auto ;
  text-align: center;
}
</style>
