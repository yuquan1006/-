<script>
    export default{
        data(){
            return {count: 0}
        }
    }
</script>

<template>
    <button @click="count++">
        count is {{ count }}
    </button>
</template>

<style scoped>
    button{
        font-weight: bold;
        background-color: red;
    }
</style>