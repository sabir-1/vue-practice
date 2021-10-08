<template>
    <h1>Get Checkbox & Radio Button Value</h1>
    <h3>Technology</h3>
    <label for="javascript">
        <input type="checkbox" id="javascript" value="javascript" v-model="technology"/>javascript
    </label>
    <br><br>
    <label for="Html">
        <input type="checkbox" id="Html" value="Html" v-model="technology"/>Html
    </label>
    <br><br>
    <label for="css">
        <input type="checkbox" id="css" value="css" v-model="technology"/>css
    </label>
    <h4>Technology Result:{{technology}}</h4>
    <h5> iam {{radio}} </h5>

    <h3>Technology Ratio</h3>
    <label for="developer">
        <input type="radio" id="student" v-model="radio" value="student" name="radio"/>student
    </label>
    <br> <br>
    <label for="developer">
        <input type="radio" id="developer" v-model="radio" name="radio" value="developer" />developer
    </label>
</template>

<script>
export default {
    check:'Get_Checkbox_Value',
    data(){
        return {
            technology: [],
            radio:null,
        }
    }
}
</script>