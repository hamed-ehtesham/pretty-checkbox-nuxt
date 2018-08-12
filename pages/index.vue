<template>
    <div>
        <h1>Pretty Checkbox Vue Nuxt Example</h1>

        <p-check color="primary">check 1</p-check>
        <p-check color="success">check 2</p-check>

        <p-radio name="r" color="warning">radio 1</p-radio>
        <p-radio name="r" color="danger">radio 2</p-radio>
    </div>
</template>

<script>
    const prettyCheck = require('pretty-checkbox-vue/check');
    const prettyRadio = require('pretty-checkbox-vue/radio');

    export default {
        name: 'index',

        components: {
            'p-check': prettyCheck,
            'p-radio': prettyRadio,
        },
    }
</script>

<style src="../node_modules/pretty-checkbox/dist/pretty-checkbox.min.css"></style>