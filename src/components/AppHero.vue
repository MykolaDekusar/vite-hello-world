<script>
export default {
    name: 'Jumbotron',
    data(){
        return {
            jumb: "I'm a Jumbotron",
        };
    },
}
</script>

<template>
    <h2>{{ jumb }}</h2>
</template>

<style scoped>
h2 {
    text-align: center;
    font-size: 5rem;
    color: green;
}
</style>