<template lang="pug">
    p.text-style
        {{ text }}
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    name: 'TextAm',
    props: {
        text: String
    }
})
</script>
<style lang="sass">
    .text-style
        font-family: 'Avenir', Helvetica, Arial, sans-serif
        font-size: 16px
        font-color: #2a363b
</style>
