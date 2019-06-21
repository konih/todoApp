<template>
    <div id="app">
        <navbar></navbar>
        <h1>This is the app</h1>
    </div>
</template>

<script>
    import Navbar from "./components/Navbar";

    export default {
        components: {Navbar},
        name: 'app-todo',
        data() {
            return {
                user: null,
                testMessage: 'This is a test!'
            }
        }
    }
</script>

<style scoped>

</style>
