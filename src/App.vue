<template>

<Home/>

</template>

<script>
import Home from './components/Home'
export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  font-family: arial, sans-serif;
}

input,button{
  outline: 0;
}
html,body{
  height:100%;
}

</style>
