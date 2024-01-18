<script>

/*
    Importazione componente
*/
import Hello from './components/Hello.vue';

export default {
    data() {
        return { 
            count: 0 
        }
    },
    /*
        Dichiarazione dei componenti all'interno dell'oggetto
    */
    components: {

        Hello
    },
}
</script>

<template>
    <div>
        <!--  Utilizzo del componente  -->
        <Hello/>
        
    </div>
</template>

<style scoped>

</style>