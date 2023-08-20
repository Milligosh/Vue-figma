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
    justify-content: center;
    margin: auto 0;
}.main h3{
    color: #000;
text-align: center;
font-family: Effra;
font-size: 36px;
font-style: normal;
font-weight: 900;
line-height: normal;
}

.mid{
    display: flex;
    flex-direction: row;
    gap:49px;
    justify-content: center;
}
.mid img{
    max-width: 30px;
    width:30px;
}
.block{
    display: none;
}

@media screen and (min-width:1200px) {
    .block{
    display: block;
}
.main h3{
    color: #000;
text-align: center;
font-family: 'inter';
font-size: 36px;
font-style: normal;
font-weight: 900;
line-height: normal;
}
.mid img{
    max-width: 60px;
    width:100%;
}
}
</style>