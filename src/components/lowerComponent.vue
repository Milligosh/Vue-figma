<script setup>
import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
 <div class="lower">
    <h1>
    Join us on email for <br/>
    <span>more trending topics</span>
 </h1>

 <ButtonComponent class="join" buttonText="Join Now"/>
</div>
</template>

<style scoped>
.lower{
    background-color: #A8FF35;
    padding:112px 17px 164px 18px;
    display:flex;
    flex-direction: column;
    gap:84px
}

.join{
    background-color: black;
    color:white;
    display:flex;
    justify-content: center;
    align-items: center;
    margin:0 auto
}
.lower h1{
    color: #000;
text-align: center;
font-family: Effra;
font-size: 36px;
font-style: normal;
font-weight: 900;
line-height: 112%;
}
span{
    color: #87D322;
text-align: center;
font-family: Effra;
font-size: 36px;
font-style: normal;
font-weight: 900;
line-height: 112%;
}

@media screen and (min-width:1200px) {
    .lower h1{
        color: #000;
text-align: center;
font-family: Effra;
font-size: 72px;
font-style: normal;
font-weight: 900;
    }

    span{
        color: #87D322;
text-align: center;
font-family: Effra;
font-size: 72px;
font-style: normal;
font-weight: 900;
line-height: 112%; 
    }
}
</style>