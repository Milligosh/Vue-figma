<script setup>
import cardComponentVue from './cardComponent.vue';
import cardComponent from './cardComponent.vue';
import arrowComponentVue from './arrowComponent.vue';
import reversedArrowComponent from './reversedArrowComponent.vue'
</script>

<template>
    <div class="middle">
   <div class="open">
    <h2>Open new tabs is sh*t</h2>
</div>
   <div class="main">
        <div class="arrow-part">
            <arrowComponentVue img="src/assets/imgss/arrow 4.png" url="src/assets/imgss/sec.png"/>
        </div>
       <div class="white"><cardComponent  url="src/assets/imgss/vector.png" img="src/assets/imgss/cancel.png" text="Findtrend-Elo" class="card2"/>
       </div> 
       <div class="arrow-part2">
            <reversedArrowComponent img="src/assets/imgss/arrow 6.png" url="src/assets/imgss/solution.svg"/>
        </div>
    </div>
    <p>A solution for your browser tabs and don't make your device get slower over time. Get ease and faster to discover a trend with just one tab.</p>
    </div>
    
</template>

<style scoped>
.middle{
    background-color:#A8FF35 ;
    padding:80px 14px;
    display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
   gap:32px;
   
}
.open h2{
    color: #000;
text-align: center;
font-family:'inter';
font-size: 36px;
font-style: normal;
font-weight: 700;
line-height: 112%;
}
.white{
   
    border-radius: 16px;
background: #F5F5F5;
max-width:502px ;
width: 100%;
max-height: 202px;
height: 118px;
display: flex;
justify-content: center;
align-items: center;
}
.card2{
background-color: #030303;
display: flex;
max-width: 342px;
width: 100%;

}
.middle p{
    max-width: 666px;
    width:100%;
    color: #000;
text-align: center;
font-family: 'inter';
font-size: 14px;

font-style: normal;
font-weight: 400;
line-height: 150%;
}
.arrow-part{
    display: flex;
    justify-content: right;
    margin-bottom: -40px;
}
.arrow-part2{
    display: flex;
    justify-content: left;
    
}

@media screen and (min-width:1200px){
    .open h2{
        color: #000;
text-align: center;
font-family: 'inter';
font-size: 72px;
font-style: normal;
font-weight: 700;
line-height: normal;
    }


}.main{
    display: flex;
    flex-direction: row-reverse;
    gap:28px

}.middle p{
    max-width: 666px;
    width:100%;
    color: #000;
text-align: center;
font-family:'inter';
font-size: 18px;

font-style: normal;
font-weight: 400;
line-height: 150%;
}
</style>