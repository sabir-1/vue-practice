<template>
    <h1>All Cities</h1>
    <button @click="tab='Lahore'">Lahore</button>
    <button @click="tab='Layyah'">Layyah</button>
    <button @click="tab='Lillah'">Lillah</button>
    <component :is="tab" />

</template>
<script>
import Lahore from './Lahore.vue'
import Layyah from './Layyah.vue'
import Lillah from './Lillah.vue'
export default {
    name:"Cities",
    components:{
        Lahore,
        Layyah,
        Lillah
    },
    data(){
        return{
            tab: 'Lahore'
        }
    }
}
</script>

