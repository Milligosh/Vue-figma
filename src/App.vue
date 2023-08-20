<script setup>
import ButtonComponent from './components/ButtonComponent.vue'
import TheNavbar from './components/TheNavbar.vue';
import heroSection from './components/heroSection.vue';
import middleComponent from './components/middleComponent.vue';
import Section3Component from './components/Section3Component.vue';
import SectionComponent from './components/SectionComponent.vue';
import tweetsComponentVue from './tweetsComponent.vue';
import nextLogoComponents from './nextLogoComponents.vue';
import arrowComponent from './components/arrowComponent.vue';
import DealComponents from './DealComponents.vue';
import lowerComponent from './components/lowerComponent.vue';
import footerComponent from '../footerComponent.vue';


</script>

<template>
  <header>
    <div>
      <heroSection/>
    </div>
    <div>
      <middleComponent/>
    </div>
    <div>
      <Section3Component/>
    </div>
    <div>
    <SectionComponent/>
      </div>
      <div>
        <nextLogoComponents/>
        <tweetsComponentVue/>

      </div>
        <div class="deals1">
          <h1>Get your Best Deal</h1>
          <div class="monthly"><p>Monthly</p>
          <img src="src/assets/imgss/toggler.png" alt="">
          <p>Yearly</p>
          <arrowComponent url="src/assets/imgss/Arrow 44.png " img="src/assets/imgss/Arrow 03.png"/>
          </div>
          <div class="deals">
          
          <DealComponents class="first" h3="Personal" Special="Special First packet for all" h1="$8/month" li1="Up to 5 page each group" li2="Up to 10 group page" li3="5days group page saved"/>
          
        
          <DealComponents class="second" h3="Regular" Special="Recommended for for Personal Pro" h1="$20/month" li1="Up to 15 page each group" li2="download page up to 20page" li3="Up to 10 group page" li4="15days group page saved"/>

          <DealComponents class="third" h3="Personal" Special="Special First packet for all" h1="$48/month" li1="Unlimited group pages" li2="Unlimited download page" li3="Unlimited page each group" li4="Customize sorting group pages" li5="customize group page name"  li6="30 days group page saved"/>
        </div>
      </div>
      
      <div>
        <lowerComponent/>
      </div>

      <div>
        <footerComponent/>
      </div>
  </header>

  <main>
    
  </main>
</template>

<style scoped>
.first,.third{
  background-color:white;
  border-radius: 20px;
  max-width: 360px;
width:100%;
max-height:602px;
height: 100%;
padding:30px 30px 30px 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto 0;
    align-items: center;
    gap:56px
}
.second{
  background-color: #A8FF35;
  border-radius: 20px;
  max-width: 360px;
width:100%;
max-height:602px;
height: 100%;
padding:30px 30px 30px 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto 0;
    align-items: center;
    gap:56px
}
.deals1{
  display: flex;
  flex-direction: column;
  gap:20px;
  background-color:black;
  padding-top: 80px;
}
.monthly img{
  display:flex;
  align-items: center;
}
.deals1 h1{
  color:white;
  display: flex;
  justify-content: center;
}
.monthly img{
  max-width: 104px;
  width:100%;
  max-height: 52px;
  height: 100%;
}
.top{
  display: flex;
  flex-direction:column
}.deals{
  display: flex;
  flex-direction: column;
  gap:24px;
  padding:50px 10px 80px 10px;
  justify-content: center;
  margin: 0 auto;
}
.monthly{
  display: flex;
  flex-direction: row;
  gap:24px;
  justify-content: center;
  align-items: center;
}
.monthly p{
  color: #FFF;
font-family: Inter;
font-size: 24px;
font-style: normal;
font-weight: 500;
line-height: normal;
display: flex;
align-items: center;
justify-content: center;
}
@media screen and (min-width:1200px) {
  .deals{
  display: flex;
  flex-direction: row;
  gap:20px;
  background-color:black;
  justify-content: center;
  padding-top: 20px;
  }
}
</style>
