<template>
<div>
  <Header/>
  <FormField id='formArea'/>
  <Footer/>
</div>
</template>

<script>
import Header from './Header'
import FormField from './FormField'
import Footer from './Footer'
export default {
    components:{
        Header,
        FormField,
        Footer

    }
}
</script>

<style>
#formArea{
  display: flex;
  
  flex-direction: column;
  align-items: center;
}

</style>