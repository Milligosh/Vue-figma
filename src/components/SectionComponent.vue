<script setup>
import newLogoComponent from '../newLogoComponent.vue';
</script>

<template>
<div class="section4">
    <div class="section">
        <h1>Findtrend make +1000 Startup grow</h1>
        
    </div>

    <div class="logos">
<newLogoComponent url="src/assets/imgss/microsoft.png"/>
<newLogoComponent url="src/assets/imgss/allianz.png"/>
<newLogoComponent url="src/assets/imgss/upwork.png"/>
<newLogoComponent url="src/assets/imgss/volvo.png"/>
<newLogoComponent url="src/assets/imgss/grab.png"/>
<newLogoComponent url="src/assets/imgss/verizon.png"/>
<newLogoComponent url="src/assets/imgss/coinbase.png"/>
<newLogoComponent url="src/assets/imgss/expedia.png"/>
<newLogoComponent url="src/assets/imgss/airtable.png"/>
<newLogoComponent url="src/assets/imgss/magento.png"/>
<newLogoComponent url="src/assets/imgss/carrera.png"/>
<newLogoComponent url="src/assets/imgss/bonanza.png"/>
<newLogoComponent url="src/assets/imgss/weTransfer.png"/>
<newLogoComponent url="src/assets/imgss/suzuki.png"/>
<newLogoComponent url="src/assets/imgss/algolia.png"/>
<newLogoComponent url="src/assets/imgss/heineken.png"/>
    </div>
</div>
</template>

<style scoped>
.section4{
    background-color: #fff;
    display: flex;
    flex-direction: column;
    gap:80px;
    padding:18px;
    
}
.section4 h1{
    color: #000;
text-align: center;
font-family: 'inter';
font-size: 36px;
font-style: normal;
font-weight: 900;
line-height: normal;
}
.logos{
    display: flex;
    display: grid;
    grid-template-columns:1fr 1fr;
    gap: 10px;
    justify-content:center;
    align-items:center;
    margin:0 auto;
    
}

@media screen and (min-width:1200px) {
.section4 h1{
    color: #000;
text-align: center;
font-family: Effra;
font-size: 64px;
font-style: normal;
font-weight: 700;
line-height: normal;
}
.logos{
    
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    gap: 32px;
}
.section4{
    padding:140px
}
}
</style>