<template>
    <div>
        <h1>{{name}}</h1>
    </div>
</template>

<script>
export default {
    name: 'MyName',
    props: ['name']
}
</script>

<style scoped>
    h1{
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>