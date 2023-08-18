<script setup>

</script>

<template>

    <div class="main">
        <h3>All platform connect to Findtrend</h3>
        <div class="mid">
        <img src="src/assets/imgss/facebook.svg" alt="">
        <img src="src/assets/imgss/twitter.png" alt="">
        <img src="src/assets/imgss/basketball.png" alt="">
        <img src="src/assets/imgss/popular.png" alt="">
        <img  src="src/assets/imgss/M.png" alt="" >
        <img class="block" src="src/assets/imgss/emoji.png" alt="">
        <img class="block" src="src/assets/imgss/w.png" alt="">
        <img class="block" src="src/assets/imgss/linkedin.png" alt="">

        </div>
    </div>
</template>

<style scoped>
.main{
    display: flex;
    flex-direction: column;
    gap:48px;
}
.mid{
    display: flex;
    flex-direction: row;
    gap:49px;
    justify-content: center;
}
.block{
    display: none;
}
</style>