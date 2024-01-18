<script>
    export default {
        data() {
            return { 
                AppTitle: 'La mia prima app con Vite!' 
            }
        },
    }
    </script>

<template>
    <header>
        <h1>
            {{ AppTitle }}
        </h1>
    </header>
</template>

<style scoped>
    h1{
        color: lightcoral;
        text-align: center;
    }
</style>