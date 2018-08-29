<template>
    <div class="{{name | kebabCase}}">
        <h1>{{name | kebabCase}} Component</h1>
    </div>
</template>

<script>
    export default {
        name: '{{name | kebabCase}}',
        props: [],

        data() {
            return {}
        },
        methods: {},
        watch: {},
        computed: {},
        mounted() {},
        created() {},

    }
</script>

<style scoped>

</style>
