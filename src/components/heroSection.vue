<script setup>
import ButtonComponent from './ButtonComponent.vue';
import TheNavbar from './TheNavbar.vue';
import cardComponent from './cardComponent.vue';

</script>
<template>
    <div class="hero">
        <div><TheNavbar/></div>
        <div class="hero-mid"> 
            <div class="text">
            <h1>Minimize your tabs.<br/> Find the trends </h1>
            <p>Don’t let your computer memories consumes  
                all of those browser tabs.
Findtrend  let you gathers all of your favorite website into one place.</p>
        </div>
        <div  class ="arrow-side">
            <ButtonComponent class="getStarted" buttonText="Get Started 🔥"/>
            <div class="arrow">
                <img src="src/assets/imgss/pic.png" alt="img">
                <img src="src/assets/imgss/Arrow 03.png" alt="">
            </div>
        </div>
        <div class="cardss">
            <cardComponent url="src/assets/imgss/twitter.png" img="src/assets/imgss/del.png" text="Cryptopunk-Sear " class="twitter"/>

            <cardComponent url="src/assets/imgss/popular.png" img="src/assets/imgss/cancel.png" text="Popular Design-Se" class="popular"/>

            <cardComponent url="src/assets/imgss/facebook.svg" img="src/assets/imgss/cancel.png" text="Product Design " class="facebook"/>

            <cardComponent url="src/assets/imgss/basketball.png" img="src/assets/imgss/cancel.png" text="Elon Musk-Sear" class="basketball"/>
        </div>
        </div>
    </div>
</template>
<style scoped>
.hero{
    background-color: black;
    padding:18px ;
    color:white;
    display:flex;
    flex-direction: column;
    gap:80px;
}
.text{
display: flex;
flex-direction: column;
gap:16px

}
.text h1{
    color: #FFF;
    text-align: center;
    font-family: 'inter';
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%
}
.text p{
    color: #8B8B8B;
    text-align: center;
    font-family: 'inter';
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%
}
.hero-mid{
    display: flex;
    flex-direction: column;
    gap:44px
}
.getStarted{
    display: flex;
    justify-content: center;
    background-color:#A8FF35;
    color:black 
}
.arrow img{
    display:none
}.arrow-side{
    display:flex;
    flex-direction: row;
    justify-content: center;
    gap:22px;
}
.twitter{
    transform: rotate(-4deg);
    background-color: #181818
}
.popular{
    transform: rotate(2deg);
    background-color: #181818
}
.facebook{
    transform: rotate(-2deg);
    background-color: #181818
}
.basketball{
    transform: rotate(4deg);
    background-color: #181818;
}

@media screen and (min-width:1200px) {
.text p{
    color: #8B8B8B;
text-align: center;
font-family: 'inter';
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 150%;
}
.arrow img{
    display:block
}
.getStarted{
    display: flex;
    justify-content: center;
    color: #A8FF35;
    padding: 16px 32px;
justify-content: center;
align-items: center;
gap: 10px;
max-width: 180px;
 width:100%;
 max-height: 57px;
 height: 100%;
 color:black;
}
.cardss{
    display: flex;
    flex-direction: row;
    gap:0px;
    
}
.hero{
    background-color: black;
    padding:29px 80px 109px 80px;
    
}
.twitter{
    transform: rotate(-4deg);
    background-color: #181818;
    max-width:341.226px;
    width: 100%;
    max-height: 82px;
height: 70px;
}
.popular{
    transform: rotate(2deg);
    background-color: #181818;
    margin-top: 30px;
}
.facebook{
    transform: rotate(-2deg);
    background-color: #181818
}
.basketball{
    transform: rotate(4deg);
    margin-top: 30px;
    background-color: #181818;
}

}
</style>