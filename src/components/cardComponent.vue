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
     
    max-width:341.226px;
    width: 293px;
    max-height: 82px;
height: 70px;
align-items: center;
margin: 0 auto;
}
.del{
    margin:-35px;
    background: linear-gradient(270deg, #181818 53.65%, rgba(24, 24, 24, 0.60) 100%);
}
p{
    color: #FFF;
text-align: center;
font-family: Roboto;
font-size: 23.806px;
font-style: normal;
font-weight: 400;
line-height: normal;
}

    


</style>