<template>
    <button class="icon-button"><img class="icon" src="../assets/notifications.svg"></button>
</template>
  
 <script>
  import Header from './components/Header.vue';
  
  export default {
    components: {
      Header
    }
  }
</script>
  
<style scoped>
    .icon {
        background: none;
        border: none;
    }
  
    .icon-button {
        margin-left: 28px;
        border: none;
        background-color: transparent;
        padding: 0;
        font: inherit;
        cursor: pointer;
        color: #71809B;
    }
</style>