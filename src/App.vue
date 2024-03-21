<script>
import FirstTry from './components/FirstTry.vue'

export default {
  data()
  {
    return{
      textMessage: "Hello World !"
    }
  },
  components:{
    FirstTry
  }
}
</script>

<template>
  <div class="booty">
    <h1 class="title">{{ textMessage }}</h1>
  </div>
  <FirstTry/>

  
</template>

<style>
.booty
{
  display: flex;
  justify-content: center;

  .title
  {
    background-color: palegoldenrod;
    color: #333;
  }
}
</style>
