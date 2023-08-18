<script setup>
import ButtonComponent from './components/ButtonComponent.vue'
import TheNavbar from './components/TheNavbar.vue';
import heroSection from './components/heroSection.vue';
import middleComponent from './components/middleComponent.vue';
import Section3Component from './components/Section3Component.vue';
import SectionComponent from './components/sectionComponent.vue';
import tweetsComponentVue from './tweetsComponent.vue';
import nextLogoComponents from './nextLogoComponents.vue';
import DealComponents from './DealComponents.vue';


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
          <div class="deals">
          
          <DealComponents h3="Personal" special="Special First packet for all" h1="$8/month" li1="Up to 5 page each group" li2="Up to 10 group page" li3="5days group page saved"/>

          <DealComponents h3="Regular" special="Recommended for for Personal Pro" h1="$20/month" li1="Up to 15 page each group" li2="download page up to 20page" li3="Up to 10 group page" li4="15days group page saved"/>

          <DealComponents h3="Personal" special="Special First packet for all" h1="$48/month" li1="Unlimited group pages" li2="Unlimited download page" li3="Unlimited page each group" li4="Customize sorting group pages" li5="customize group page name"  li6="30 days group page saved"/>
        </div>
      </div>
  </header>

  <main>
    
  </main>
</template>

<style scoped>
.deals1{
  display: flex;
  flex-direction: column;
  gap:20px;
  background-color:black;
}
.deals1 h1{
  color:white;
  display: flex;
  justify-content: center;
}
.top{
  display: flex;
  flex-direction:column
}.deals{
  display: flex;
  flex-direction: column;
  gap:40px
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
