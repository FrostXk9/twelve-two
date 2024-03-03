<template>
    <div id="card">

        {{ cardContent }}

        <div>
            
            <button>{{ cardhref }}</button>

        </div>
    </div>
</template>
<script setup>
defineProps({
    cardContent: String,
    cardhref: String
})
</script>
<style>
    #card{
        width: 50%;
        display: flex;
        justify-content: center;
        flex-direction: column;
        border: 1px solid black;
    }
</style>