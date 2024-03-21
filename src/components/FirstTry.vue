<script>

export default {
  name: "FirstTry",
  data() {
    return {
      nameComp: "Hello ?"
    }
  }
}

</script>

<template>
  <div class="test">
    <p>{{ nameComp }}</p>
    <img src="/image/vite.svg" alt="">
  </div>
</template>

<style>
.test
{
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;

  p 
  {
    text-align: center;
    font-size: 50px;
    color: palegreen;
  }

  img 
  {
    width: 100%;
    max-width: 200px;
  }
}
</style>
