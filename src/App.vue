<script>
/* import FirstTry from './component/FirstTry.vue' */

export default {
  data()
  {
    return{
      textMessage: "Hello World !"
    }
  }
}
</script>

<template>
  <div class="booty">
    <h1 class="title">{{ textMessage }}</h1>
  </div>
  
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
