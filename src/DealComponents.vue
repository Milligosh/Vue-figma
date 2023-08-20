<script setup>
import ButtonComponent from './components/ButtonComponent.vue';
defineProps(['h3','Special','h1','li1','li2','li3','li4','li5','li6'])
</script>

<template>
<div class="deal">
    <div class="cards">
        <div class="card">
        <h1>{{ h3 }}</h1>
        <p>{{Special}}</p>
        </div>
        <div class="ul">
            <h1>{{ h1 }}</h1>
            <ul>
                <li>.{{li1}}</li>
                    <li>{{li2}}</li>
                    <li>{{ li3 }}</li>
                    <li>{{li4}}</li>
                    <li>{{ li5 }}</li>
                    <li>{{ li6 }}</li>
                    
                
            </ul>
            <ButtonComponent class="button" buttonText="Start Free trial"/>
        </div>
    </div>

</div>
        
</template>

<style scoped>
.deal{
    background-color:black;
    display: flex;
    justify-content: center;
    margin: auto 0;
    align-items: center;

}
.button{
    display: flex;
    justify-content: center;
    background-color: black;
    color:white;
    border:none
}
.cards{
    
    
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
.card h1{
    color: #000;
font-family: 'inter';
font-size: 32px;
font-style: normal;
font-weight: 400;
line-height: 100%; 
}
.card{
    display:flex;
    flex-direction: column;
    gap:14px
}
.card h1{
    color: #000;
font-family: 'inter';
font-size: 36px;
font-style: normal;
font-weight: 400;
line-height: 100%;
}
.ul{
    display: flex;
    flex-direction: column;
    gap:27px
}
.ul h1{
    color: #000;
font-family: 'inter';
font-size: 60px;
font-style: normal;
font-weight: 400;
line-height: 100%;
}
ul{
    display: flex;
    flex-direction: column;
    gap:30px
}
li,.card p{
    color: #000;
font-family: 'inter';
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 100%;
}
</style>