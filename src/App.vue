<template>
    <div id="app">
        <workflow></workflow>
    </div>
</template>

<script>
    import Workflow from './components/Workflow';

    export default {
        name: 'App',
        components: {
            Workflow
        }
    }
</script>

<style>
    body {
        margin: 0;
    }
</style>