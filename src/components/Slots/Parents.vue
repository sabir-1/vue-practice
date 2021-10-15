<template>
<h1>The Parent Component</h1>
<Child>
    <template v-slot:header>
        <h3>Sabir khan header</h3>
    </template>
    <template v-slot:main>
        <h3>Sabir khan main</h3>
    </template>
    <template v-slot:footer>
        <h3>Sabir khan footer</h3>
    </template>
</Child>

</template>

<script>
import Child from './Child.vue'
export default {
    slot: "Parent",
    components: {
        Child
    },
    data() {
        return {
            Child
        }
    }
}
</script>
