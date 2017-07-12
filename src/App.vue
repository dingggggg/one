<template>
    <div id="app">
        <ahead></ahead>
        <amenu></amenu>
    </div>
</template>

<script>

import Head from './components/header.vue'
import Menu from './components/menu.vue'

export default {
    name: 'app',
    data: function (){
        return {
            show : true
        }
    },
    components: {
        ahead: Head,
        amenu: Menu
    }
}
</script>

<style>

</style>
