<template>
    <div class="home">
        <h1>{{ out }}</h1>
    </div>
</template>

<script>
    export default {
        name: "homeScreen",
        props: {
            out: String
        }
    }
</script>