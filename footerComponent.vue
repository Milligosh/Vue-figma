<script setup>

</script>

<template>
<div class=" footer">
    <div class="logo">
    <img src="src/assets/imgss/black.png" alt="">
    <h1>Findtrend</h1>
</div>
    <div class="list">
        <p> Privacy Policy</p>
        <p> Terms and Conditions</p>
        <p> Contact Us</p>
        <p> Careers</p>
        
    </div>
</div>
</template>

<style scoped>
.footer{
    background-color: #fff;
    display: flex;
    flex-direction: column;
    gap:32.99px;
    padding-bottom: 80px;
    

}
.logo{
    display:flex;
    flex-direction: row;
    gap:10.32px;
    padding:70px 148px 70px 113px;
}
.logo h1{
    color: #000;
text-align: center;
font-family: 'Inter';
font-size: 24px;
font-style: normal;
font-weight: 700;
line-height: 100%;
display: flex;
align-items: center;
}
.logo img{
    max-width: 40px;
    width:100%;
    max-height: 40px;
}
.list{
    display: flex;
    flex-direction: column;
    gap:40px;
    margin: 0 auto;
    /*padding:107px 103px 80px 103px;*/
}
.list p{ 
    color: #000;
text-align: center;
font-family: 'inter';
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 100%; 
}
@media screen and (min-width:1200px) {
.footer{
    background-color: #fff;
    display: flex;
    flex-direction: row;
    gap:32.99px;
    padding-bottom: 0px;

}
.logo{
    display:flex;
    flex-direction: row;
    gap:10.32px;
    justify-content: center;
    align-items: center;
    
}
.list{
    display: flex;
    flex-direction: row;
    gap:40px;
    justify-content: center;
    align-items: center;
    
    
}
}
</style>