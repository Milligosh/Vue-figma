<script setup>
defineProps(['url'])
</script>

<template>
 <div class="logo">
    <img :src="url" alt="">
 </div>
</template>

<style scoped>
.logo{
    max-width: 266px;
    width: 100%;
    max-height: 120px;
    height: 100%;
    background-color: #f5f5f5;
    border-radius: 8px;
    padding: 25px 24px;
    display: flex;
    align-items: center;
}

.logo img{
   max-width: 105.97px;
   width: 100%;
max-height: 25.579px;
height: 100%;
}
</style>