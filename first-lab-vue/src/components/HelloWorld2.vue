
<script>
export default {
    data() {
        return {
            title: 'Second component',
        }
    },
    methods: {
        showHelloWorld() {
            console.log('hello world')
        },
    }
}

</script>
<template>
    <h1>{{title}}</h1>
    <button @click="showHelloWorld"> Press me</button>
</template>
<style scoped>
</style>