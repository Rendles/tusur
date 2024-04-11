<!-- 
ToDo:
1. Добавить бордер у header -->

<template>
  <body>
    <Header/>
    <div class="page">
      <div class="menu">ваы</div>
      <div class="main-page">ыва</div>
    </div>
  </body>
</template>

<style scoped>

  body{
    padding: 0px 0px;
  }

  .page{
    display: flex;
  }

  .menu{
    display: flex;
    width: 20%;
    background-color: aqua;
  }

  .main-page{
    display: flex;
    width: 80%;
    background-color: blueviolet;
  }
</style>


<script>
import Header from './components/Header.vue';

export default {
  components: {
    Header
  }
}
</script>
