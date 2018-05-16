<template>
    <div id="app"></div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import HelloWorld from './components/Footer'

export default {
  name: 'app',
  components: {
    
  },
  data(){
    return {
      code:'xx'
    }
  },
  created(){
    var n=0
    setInterval(()=>{
      this.code=n
      n+=1
    },1000)
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
  margin-top: 60px;
}
</style>
