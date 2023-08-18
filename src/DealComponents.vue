<script setup>
import ButtonComponent from './components/ButtonComponent.vue';
defineProps(['h3','Special','h1','li1','li2','li3', 'li4','li5','li6'])
</script>

<template>
<div class="deal">
    <div class="cards">
        <div class="card">
        <h3>{{ h3 }}</h3>
        <p>{{Special}}</p>
        </div>
        <div>
            <h1>{{ h1 }}</h1>
            <ul>
                <li>.{{li1}}</li>
                    <li>{{li2}}</li>
                    <li>{{ li3 }}</li>
                
            </ul>
            <ButtonComponent class="button" buttonText="Start Free trial"/>
        </div>
    </div>

</div>
        
</template>

<style scoped>
.deal{
    background-color:black;
    padding:50px,10px;
    display: flex;
    justify-content: center;
    margin: auto 0;
    align-items: center;

}
.button{
    display: flex;
    justify-content: center;
}
.cards{
    border-radius: 20px;
    background-color: white;
max-width: 300px;
width:100%;

    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto 0;
    align-items: center;
    gap:20px
}
</style>