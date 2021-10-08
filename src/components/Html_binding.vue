<template>
<h1> Html Binding {{text}} </h1>
<div v-html="tag">

</div>
<div v-html="tag2">

</div>
</template>

<script>
export default {
    binding: 'Html_binding',
    data() {
        return {
            text: "this is text",
            tag: "<h1>Sabir Khan</h1>",
            tag2: "<p>Sabir awan</p>",
        }
    }

}
</script>
