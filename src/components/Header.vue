<template>
  <div class="header">

      <div class="items">

      <a id="links" href="#"><p>Gmail</p></a>
      <a id="links" href="#" ><p>Images</p></a>

      <a href="#" ><img src="../assets/googleApps.svg" id='googleApps'></a>

      <img id="perfil" src="https://lh3.googleusercontent.com/ogw/ADGmqu8RK7gCyPqOs3KHIu4MS0B1NfSkqFwZ641ZYXjxbA=s32-c-mo" >

      </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>

.items{
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 30px;
    padding: 15px ;

    width: 241px;


    
    
}

.header{
display: flex;
    align-items: center;
    justify-content: flex-end;

    height: 31px;
    width: 100%;




}

img#googleApps{
    border-radius: 0;
    height: 17px;
    width: 16px;
    margin:6px -10px 0 1px ;
    opacity: 0.5;
}

img#googleApps:hover{
    opacity: 1;
}

img#perfil{
    height: 32px;
    width: 32px;
    border-radius: 50%;

    cursor: pointer;
}

a{
    text-decoration: none;
}

a#links:hover{
    text-decoration:underline black;
   
}

p{
    font-size: 13px;
    color:black;
    margin: auto -7px;
}

p:hover{
    color: rgb(79, 79, 79);
}

</style>