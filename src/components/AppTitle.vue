<script>
export default {
    name: 'Title',
    data(){
        return{
            title: 'La mia prima app con Vite!',
        };
    },
}
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style scoped>
h1 {
    font-size: 6rem;
    text-align: center;
    margin-bottom: 5rem;
    color: red;
}
</style>