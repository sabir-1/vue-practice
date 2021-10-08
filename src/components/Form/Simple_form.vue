<template>
<h1>Simple Form</h1>
<ul>
    <li v-for="item in error" v-bind:key="item" > {{item}} </li>
</ul>


    <label>password</label><br>
    <input type="email" v-model="form.email" />

    <br>

    <label>password</label><br>
    <input type="password" v-model="form.password" />
    <br><br>
    <select v-model="form.country" >
        <option>India</option>
        <option>Usa</option>
        <option>Iran</option>
    </select>
    <br><br>
    <h3>Teachnology</h3>
    <label>Vue js</label>
    <input type="checkbox" value="vue" v-model="form.teachnology" />
    <br/>
    <label>React js</label>
    <input type="checkbox" value="react" v-model="form.teachnology" />
    <br><br>
    <h3>Gender</h3>
    <label>Male</label>
    <input type="radio" value="Male" name="gender" v-model="form.gender"/>
    <br/>
    <label>Female</label>
    <input type="radio" value="Female" name="gender" v-model="form.gender"/>
     <br/> <br/>

    <button v-on:click="getValue()">Submit</button>

</template>

<script>
export default {
    output: "Simple_form",
    data() {
        return {
            form: {
                email: "",
                password: "",
                country: "",
                teachnology:[],
                gender:""
            },
            error:[]
        }
    },
    methods: {
        getValue() {
            this.error = [];
            for(const item in this.form){
                 if(this.form[item]==="" || this.form[item].length===0){
                     this.error.push(item)

                 } 
            }
            if(this.error.length===0){
                alert("data is submitted")

            }
            console.warn("forms", this.form, this.error)
        }
    }
}
</script>
