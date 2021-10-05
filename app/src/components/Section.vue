<template>
<section class="sessao">
    <h2 class="titulo-sessao">Find Your Best Psychic Advisor</h2>
    <div class="container">
    
    <div class="item">
        <div class="imagem-item"><img src="../assets/img/meninadeoculos.jpg" alt="Meninadeoculos"></div>
        <div class="texto">
            <p class="nome">Merry Healer</p>
            <p class="nome-1">help with all matters of life. Such as Love Health happiness, and Career. I will also give you, sense of direction. I am a Life coach, My readings come directly from the heart I do not sugarcoat, I am nonjudgmental. all of my readings are private and confidential. I will lead you and guide you to your heart's desires.</p>
            
        </div>
        <div class="botoes">
        <p class="minuto">First 3 Minutes Free</p>
        <p class="valor">$4.99/min</p>
        <button class="chamada"> <img class="telefone" src="../assets/img/telefone.svg" alt="telefone"> Call Now</button>
        <button class="chamada-1"> <img class="telefone-1" src="../assets/img/chat.svg" alt="chat">Chat Later</button> 
        </div>

    </div>

    <div class="item">
        <img class="imagem-item" src="../assets/img/meditacao.jpg" alt="Meditando">
        <div class="texto">
            <p class="nome">Superloveadvisor</p>
            <p class="nome-1">Improve your life today</p>
            <p class="nome-1">I'm proud to say that I have guided many clients to their financial breakthrough and overall happiness. I've lead many on the right career path as well as helped them through every difficult time.</p>
        </div>
        <div class="botoes">
        <p class="minuto">First 3 Minutes Free</p>
        <p class="valor">$3.99/min</p>
        <button class="chamada-2"> <img class="telefone-1" src="../assets/img/email.svg" alt="chat">Send Mail</button>
        <button class="chamada-1"> <img class="telefone-1" src="../assets/img/chat.svg" alt="chat">Chat Now</button>
        </div>
        </div>
    <div class="item">
        <img class="imagem-item" src="../assets/img/mulhercomalua.jpg" alt="Mulhercomalua">
        <div class="texto">
            <p class="nome">Psychic Althea</p>
            <p class="nome-1">Keen's Amazing Psychic Astrologer RexFrederick</p>
            <p class="nome-1">Hello Keen clients! My name is Rex! Quick, friendly, fun, and Accurate! Over 60,000 readings here on Keen! Love, Marriage, Finance and Your Well Being! I'm here to serve your every need! Detailed w/Real understanding!</p>
            
        </div>
        <div>
        
    </div>
    <div class="botoes">
        <p class="minuto">First 3 Minutes Free</p>
        <p class="valor">$5.99/min</p>
        <button class="chamada"><img class="telefone" src="../assets/img/telefone.svg" alt="telefone">Call Now</button>
        <button class="chamada-1"> <img class="telefone-1" src="../assets/img/chat.svg" alt="chat">Chat Now</button>
    </div>

    
    </div>
    
    <div class="botao-inferior">
        <button class="advisors">See More Advisors</button>
        <button class="matched">Get Matched</button>
        <img class="seta" src="../assets/img/Setas.svg" alt="setas">
        <img class="letras-texto" src="../assets/img/Letras.svg" alt="Letras"></div>
    </div>
</section>
</template>

<style lang="scss">

.titulo-sessao{
    background: #09B3B0;
    color: #ffffff;
    margin: 0;
    padding: 10px;
    font-family: Yrsa;
    font-style: normal;
    font-weight: normal;
    text-align: center;
    font-size: 18px;
}
.item{
    display: flex;
    text-align: left;
    font-size: 11px;
    color: #09292F;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    align-items: center;
    flex: 1;
    width: 100%;
    margin-bottom: 15px;
}
.imagem-item{
    width: 20%;
    display: flex
    
}
.imagem-item img{
    display: flex;
    width: 100%;
}
.botoes{
    width: 15%;
    display: flex;
    flex-direction: column;
}
.texto{
    width: 65%;
    display: flex;
    flex-direction: column;
    padding: 5px;
}
.container{
    padding: 40px 60px;
    background-image: url('../assets/img/960x0-21.jpg');
    background-size: cover;
}
.nome{
color: #008080;
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 17px;
margin-left: 5px;
margin-top: -24px;
}
.minuto{
background: #09B3B0;
border-radius: 3px 0px 0px 3px;
color: #fff;
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 7px;
text-align: center;
margin: 0px 0px 5px 0px;
padding: 0px;
margin: 0px;

}
.valor{
    display: block;
        color: black;
        font-family: Roboto;
        background: white;
        font-style: normal;
        font-weight: normal;
        padding-top: 8px;
        text-align: end;
        margin-bottom: 13px !important;
        padding: 0px;
        display: flex;
        margin: 0px 0px;
}
.chamada{
    background: #FF9F00;
border: 1px solid #FF9F00;
box-sizing: border-box;
border-radius: 2px;
    color: white;
    width: 100%;
    font-size: 0.9em;
    padding: 2px;
    margin-bottom: 10px
}
.chamada-1{
background: #09B3B0;
border: 1px solid #09B3B0;
box-sizing: border-box;
border-radius: 2px;
color: white;
width: 100%;
font-size: 0.9em;
padding: 2px;
}
.chamada-2{
background: #FFFFFF;
border: 1px solid #09B3B0;
box-sizing: border-box;
border-radius: 2px;
color: #09B3B0;
width: 100%;
font-size: 0.9em;
padding: 2px;
margin-bottom: 5px;
}
.telefone{
    width: 17%;
    margin: 2px 5px 0px 0px;
    margin-bottom: -2px;
}
.telefone-1{
    margin: 2px 5px 0px 0px;
    margin-bottom: -2px;
    width: 15px;
}
.nome-1{
    margin-top: 0px;
    margin-left: 5px;
}
.advisors{
background: #09B3B0;
border: 1px solid #09B3B0;
box-sizing: border-box;
border-radius: 2px;
color: white;
font-size: 0.7em;
margin-right: 15px;
height: 28px;
padding-left: 40px;
padding-right: 40px;
}
.botao-inferior{
    display: flex;
    justify-content: center;
    margin-top: 20px;
}
.matched{
background: #FF9F00;
border: 1px solid #FF9F00;
box-sizing: border-box;
border-radius: 2px;
color: white;
font-size: 0.7em;
margin-right: 15px;
height: 28px;
padding-left: 40px;
padding-right: 40px;
}
.seta{
width: 4%;
margin-top: -33px;
font-family: Roboto;
font-style: normal;
font-weight: normal;    
}
.letras-texto{
    width: 10%;
    margin-top: -33px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
}
</style>