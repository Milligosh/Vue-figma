<script scoped>
defineProps(['img'])
</script>

<template>

    <div>
        <div class="logo">
            <img :src= "img" alt="imgg">
        </div>
    </div>
</template>

<style scoped>
.logo{
    display: flex ;
    max-width: 266px;
    width:100%;
max-height: 120px;
height: 100%;
border-radius: 8px;
background: #F5F5F5;
    }
</style>