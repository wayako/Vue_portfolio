<template lang="pug">
    span
        .button-am
            template(v-if="buttonType === "clickButton"")
                button(type="button", :value=textehoge, )
    
    
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    name: 'ButtonAm',
    props: {
        buttonType: {
           type: String,
           default: "clickButton"
        }
    }
    
})
</script>
<style lang="sass">
.button-am
    height: 20px
    widt: 40px
</style>

