<template>
    <header>
      <div class="logo-container">
        <img src="../assets/logo.svg">
      </div>
      <div class="main-container">
        <div class="left-section">
          <div class="vertical-line"></div>
          <button class="icon-button"><img class="icon" src="../assets/notifications.svg"></button>
          <button class="icon-button"><img class="icon" src="../assets/chat.svg"></button>
          <button class="icon-button"><img class="icon" src="../assets/calendar.svg"></button>
        </div>
        <div class="right-section">
          <img class="avatar" src="../assets/photo.png">
          <span class="user-name">Иван Иванов</span>
          <div class="vertical-line"></div>
          <button class="exit">Выход</button>
        </div>
      </div>
    </header>
  </template>
  
  <style scoped>
  header {
    padding: 0px;
    margin: 20px;
    display: flex;
  }
  
  .logo-container {
    width: 20%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .main-container {
    width: 80%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .left-section,
  .right-section {
    display: flex;
    align-items: center;
  }
  
  .vertical-line {
    height: 38px;
    border-left: 1px solid #DADDE5;
  }
  
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
  
  .avatar {
    margin-right: 20px;
  }
  
  .user-name {
    margin-right: 30px;
    color: #71809B;
  }
  
  .exit {
    margin-left: 30px;
    margin-right: 45px;
    background: none;
    border: none;
    padding: 0;
    cursor: pointer;
    color: #71809B;
  }
  </style>
  
  <script>
  export default {}
  </script>
  