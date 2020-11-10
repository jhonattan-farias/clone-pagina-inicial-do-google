<template>
<div class="footer">
    <span>Brazil</span><hr>
        <div class="Space">
                <div class="firstField">
                <a href="#">Adversiting</a>
                <a href="#">Business</a>
                <a href="#">About</a>
                <a href="#">How Search Works</a>
                </div>

                <div class="secondField">
                    <a href="#">Privacy</a>
                    <a href="#">Terms</a>
                    <a href="#">Settings</a>
                </div>

        </div>

        
</div>
</template>

<script>
export default {

}
</script>

<style>



.footer{
    display: flex;
    flex-direction: column;
    border-top: 1px solid rgba(179, 175, 175, 0.5);


    max-width: 100%;
    background: rgba(186, 185, 185, 0.2);
    

}

span{
    margin: 13px 0 10px 29px;
    font-size:9pt;
    color: rgba(0,0,0,0.6);
}

hr{
    opacity: 0.4;
}

.Space{
    display: flex;
    justify-content: space-between;
    align-items:center;
}

.firstField{
    display: flex;

    align-items: center;
}

a{
    color: rgba(0,0,0,0.6);
    font-size: 8.5pt;
    margin: 15px 10px;

}

a:hover{
    text-decoration: underline;
}
</style>