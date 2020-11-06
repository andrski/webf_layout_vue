<template>
  <div>
    <Header />
    <MainScreen />
    <SecondMainScr />
    <Footer />
  </div>
  
</template>

<script>
import Header from './components/Header.vue'
import MainScreen from './components/MainScreen.vue'
import SecondMainScr from './components/SecondMainScr'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    MainScreen,
    SecondMainScr,
    Footer
  }
}
</script>

<style>

   html{
      box-sizing: border-box;
  }
  *, *::before, *::after{
      box-sizing: inherit;
  }
  body{
    max-width: 1920px;
    max-height: 9835px;
    margin: 0px;
    background:  #F2F2F2; 
  }
</style>
