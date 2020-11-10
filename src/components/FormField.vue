<template>
<div class="formArea">
    <div class="googleField"><img id='googleLogo' src="https://www.google.com.br/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="">
    
    <div class="inputArea">
        <img src="../assets/lupa.svg" id='lupa'>
        <input type="text">
        <img id='mic' src="../assets/mic.svg" >
    </div>

    <div class="searchButtons">

        <button id="searchButton">Pesquisar no Google</button>
        <button id="searchButton">Estou com sorte</button>
    
    </div>

    <p id='googleOffered'>Google Offered in: <a href="">Português (Brasil)</a></p>
</div>

    

</div>
    
</template>

<script>
export default {

}
</script>

<style>

.formArea{
    display: flex;
    align-items: center;
    justify-content: center;

    min-height: calc(99vh - 41px - 70px);

    }

.googleField{
  margin-top: 70px;

  display: flex;

  flex-direction: column;
  align-items: center;
  justify-content: center;


    
  flex:1;


}
img#googleLogo{
    margin-top: 30px;

    height: 85px;
    width: 247px;


}

.inputArea{
    width: 440px;
    height: 43px;
    margin-top: 30px;
    display: flex;

    justify-content: center;



    border: 1px solid rgba(211, 206, 206,0.6);
    border-radius: 30px;
}

.inputArea:hover{
    box-shadow: 0 0.5px 5px rgba(114, 114, 114, 0.5) ;
    border: 0;
}

input{
    display: flex;
    border: 0;
    flex: 1;

    font-size: 11pt;

}

img#lupa{
    width: 13px;
    height: 13px;

    margin: auto  15px;

    opacity: 0.5;
}

img#mic{
    width: 20px;
    height: 20px;

    margin: 11px 13px 0 0;

    cursor: pointer;
}

.searchButtons{
    display: flex;
    justify-content: space-around;

    width: 100%;
    height: 35px;
    padding:0 80px ;
    margin-top: 25px;

}

button#searchButton{
    background-color: rgb(250, 248, 248);
    border: 0;
    border-radius: 1.6px ;
    color: rgb(58, 58, 58);
    padding: 0 15px;
    margin: 0 5px;
    cursor: pointer;
}

button#searchButton:hover{
    box-shadow: -0.1px 0.2px 3px rgb(116, 116, 116);
}

p#googleOffered{
    color: rgba(0, 0, 0, 0.9);
    font-size: 11.5px;
    margin-top: 25px;
}

p#googleOffered a{
    margin-left: 5px;
    color: blue;
}

</style>