<script>
    import PrimaryButton from '../utilities/PrimaryButton.vue';
    import SecundaryButton from '../utilities/SecundaryButton.vue';
    export default{
        components:{
            PrimaryButton,
            SecundaryButton
        },
    }
</script>

<template>
    <div class="conteiner">
        <div class="texto">
            <h1>Transforme</h1>
            <h2>algo que sobra em algo que</h2> 
            <h1>soma</h1>
        </div>
        <img src="@/assets/icons/Imagem-Principal-Home.png" id="initial-image"> 
    </div>
</template>

<style>
    .conteiner{
        display: grid;
        grid-template-columns: 2fr 2fr; /* Ele divide os elementos proporcionalmente na tela*/
    }
    #initial-image{
        width: 100%;
        height: 100%
    }
    
    .texto{
        position: absolute;
        top: 10%;
        left: 10%;
        padding: 200px;
        color: #fff;
    } 
</style>