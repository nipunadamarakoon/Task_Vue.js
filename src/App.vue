<template>
  <div id="app">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
    <Navbar />
      <GetStart/>
      <AdvanceStatics/>
      <BootsLink/>
      <Footer/>


  </div>
</template>

<script>

import Navbar from './components/NavBar'
import GetStart from './components/GetStart'
import AdvanceStatics from './components/AdvanceStatistic'
import Footer from './components/Footer'
import BootsLink from './components/BootsLink'
export default {
  name: 'app',
  components: {
    BootsLink,
      AdvanceStatics,
      GetStart,
    Navbar,
    Footer,

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: -25px;
}
</style>
