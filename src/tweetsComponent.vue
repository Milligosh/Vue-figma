<script setup>
import ButtonComponent from './components/ButtonComponent.vue';
</script>

<template>
    <div class="tweets">
        <img src="src/assets/imgss/tweet 1.png" alt="">
        <img src="src/assets/imgss/tweet 2.png" alt="">
        <img src="src/assets/imgss/tweet 3.png" alt="">
        <ButtonComponent class="button" buttonText="View more trends"/>
    </div>
</template>

<style scoped>
.tweets{
    display:flex;
    flex-direction: column;
    gap:43px;
    padding:18px;
    max-width:800px;
    width: 100%;
    justify-content: center;
    margin:0 auto;
    padding-bottom: 92px;

}
.button{
    display: flex;
    justify-content: center;
    max-width:198px;
    margin:0 auto;
    background-color:black;
    color:white
}
</style>