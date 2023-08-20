<script setup>
defineProps(['url','text','img'])
</script>

<template> 
<div class="cards">
    <img :src="url" alt="">
    <p>{{ text }}</p>
    <img :src="img" alt="" class="del">
</div>

</template>

<style scoped>
.cards{
    display: flex;
    flex-direction: row;
    gap:14px;
     border: 1px solid rgb(49, 45, 45);
    max-width:341.226px;
    width: 100%;
    max-height: 82px;
height: 70px;
align-items: center;
margin: 0 auto;
box-shadow: 0px,12px 6px white;;
}
.del{
    margin:-35px;
    background: linear-gradient(270deg, #181818 53.65%, rgba(24, 24, 24, 0.60) 100%);
    transform: rotate(-4deg);
    max-width: 16px;
    width: 100%;
    max-height: 16px;
    height: 100%;
    z-index: 1;
}
p{
    color: #FFF;
text-align: center;
font-family: 'inter';
font-size: 23.806px;
font-style: normal;
font-weight: 400;
line-height: normal;
display: flex;
justify-content: center;
margin:auto 0;
}

    


</style>