<template>
    <div class="chart">
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: "Chart",
        props: [],
        data() {
            return {
                
            }
        },
        methods: {
        }
    }
</script>

<style scoped>
    .chart {
        max-width: 500px;
    }
</style>