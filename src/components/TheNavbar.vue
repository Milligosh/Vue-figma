<script setup>
import ButtonComponent from './ButtonComponent.vue'
</script>

<template>
    <header>
        <div class="findLogo">
          <img src="src/assets/imgss/vector.png" alt="logo"> 
          <h2>Findtrend</h2> 
        </div>

        <div class="top-links">
            <p>About</p>
            <p>How it works</p>
            <p>Pricing</p>
            <p> Solutions</p>
            <p>Features</p>
        </div>

        <div class="hamburger">
            <img src="src/assets/imgss/hamburger.png" alt="hamburger">
            <p>LogIn</p>
            <ButtonComponent class="button" buttonText="Register"/>

        </div>

        
    </header>
</template>

<style scoped>


header{
    display:flex;
    flex-direction: row;
    justify-content: space-between;
}
.top-links{
    display: none;
    
    
}
.findLogo h2{
    display: none;
}
.button{
 display:none;
}
.hamburger p{
    display: none;
}


@media screen and (min-width:1200px) {
    .top-links{
    display: block;
    display:flex;
    flex-direction: row;
    gap:40px;
    align-items: center;
}
.top-links p{
    color: #FFF;
    text-align: center;
    font-family:'Inter';
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%;
}
.findLogo h2{
    display: block;
    color: #FFF;
    text-align: center;
    font-family: 'Inter';
    font-size: 24px;
    font-style: normal;
    font-weight: 700;
line-height: 100%
} 
.findLogo{
    display:flex;
    flex-direction: row;
    gap:10px;
}
.findLogo h2{
    display: flex;
    align-items:center ;
}
.hamburger img{
    display: none;
}
.hamburger{
    display: flex;
    flex-direction: row;
    gap:20px
}
.hamburger p{
    display: block;
    display: flex;
    align-self: center;
}
.button{
 display:block;
 display: inline-flex;
 

}
}
</style>
