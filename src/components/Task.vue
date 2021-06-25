<template>
    <h3> {{ task.text }}</h3>
</template>

<script lang = "ts">
    export default {
        props: {
            task: Object
        }
    }
</script>
