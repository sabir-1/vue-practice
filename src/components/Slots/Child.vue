<template>
    <!-- <slot></slot> -->

    <div class="wrap">
        <header>
            <slot name="header"></slot>
        </header>
        <main>
            <slot name="main"> </slot>
            <button>click</button> 
        </main>
        <footer>
            <slot name="footer"></slot>
        </footer>
    </div>
</template>

<script>
export default {
    slot:'Child',
    
}
</script>