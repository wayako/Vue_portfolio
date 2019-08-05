<template lang="pug">
    ul.header-mc-ul
        li(v-for="menu in menus").hedaer-mc-li
            a.header-mc-text
                {{ menu }}
    
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    data: {
        menus: [
            'Profile',
            'Skills',
            'Works',
            'Contact'
        ]
    }
})
</script>
<style lang="sass">
    .header-mc-ul
        list-style: none

    .header-mc-ul
        text-align: center
        background-color: #eb4a5f

    .header-mc-text
        text-decoration: none
        color: #dddddd
        font-wright: bold
</style>
