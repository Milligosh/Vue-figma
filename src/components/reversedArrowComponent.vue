<script setup>
defineProps(['url','img'])
</script>

<template>
 <div class="arrow">
                <img :src="url" alt="img" class="img">
                <img :src="img" alt="img" class="img2">
            </div>
</template>

<style scoped>
.arrow{
    display: flex;
    flex-direction: column;
}
.img{
    max-width: 93px;
    width: 100%;
    
}
.img2{
    max-width: 93px;
    width: 100%;
}
</style>