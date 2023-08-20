<script setup>
defineProps(['buttonText'])
</script>

<template>
    
        <button>{{ buttonText }}</button>
    
</template>

<style scoped>
button{
    padding: 12px 32px;
justify-content: center;
align-items: center;
gap: 10px;
border-radius: 40px;
border:none;
}
</style>