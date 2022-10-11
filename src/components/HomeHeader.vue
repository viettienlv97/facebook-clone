<template>
  <div class="header">
    <div class="logo">
        <img src="../assets/Logo/Facebook.png" alt="" class="logo-img">
    </div>
    <div class="search-bar">
      <svg class="search-icon" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="15" height="15" viewBox="0 0 16 16">
        <g>
        </g>
        <path d="M16.604 15.868l-5.173-5.173c0.975-1.137 1.569-2.611 1.569-4.223 0-3.584-2.916-6.5-6.5-6.5-1.736 0-3.369 0.676-4.598 1.903-1.227 1.228-1.903 2.861-1.902 4.597 0 3.584 2.916 6.5 6.5 6.5 1.612 0 3.087-0.594 4.224-1.569l5.173 5.173 0.707-0.708zM6.5 11.972c-3.032 0-5.5-2.467-5.5-5.5-0.001-1.47 0.571-2.851 1.61-3.889 1.038-1.039 2.42-1.611 3.89-1.611 3.032 0 5.5 2.467 5.5 5.5 0 3.032-2.468 5.5-5.5 5.5z" fill="#000000" />
      </svg>
      <input type="text" placeholder="Tìm kiếm trên Facebook">
    </div>
    <div class="nav-list">
      <div class="nav-item nav-messenger"><img src="../assets/Logo/messenger.png" alt=""></div>
      <div class="nav-item nav-notifi"></div>
      <div class="nav-item nav-user"></div>
    </div>
  </div>
</template>

<style scoped>
  .header{
    width: 100%;
    height: 56px;
    position: fixed;
    display: flex;
    align-items: center;
    box-shadow: 1px 1px 2px #ccc;
  }
  .logo{
    width: 120px;
    position: absolute;
    top: -10px;
    left: 19px;
  }
  .logo-img{
    width: 100%;
  }
  .search-bar{
    margin: 0 calc(50% - 380px) ;
    width: 680px;
    height: 40px;
    border-radius: 30px;
    background-color: #f0f2f5;
    display: flex;
  }
  .search-bar:hover{
    cursor: text;
  }
  .search-bar>input{
    border: none;
    background-color: #f0f2f5;
    width: 90%;
    margin-left: 10px;
    font-size: 15px;
  }
  .search-bar>input:focus{
    outline: none;
  }
  .search-icon{
    margin-left: 13px;
    align-self: center;
  }
  .nav-list{
    display: flex;
    margin-right: 16px;
    width: 160px;
    height: 100%;
  }
  .nav-item{
    background-color: #f0f2f5;
    width: 40px;
    border-radius: 50%;
    height: 40px;
    margin: 8px 0 0 8px
  }
  .nav-item:hover{
    cursor: pointer;
  }
  .nav-item.nav-messenger{
    text-align: center;
  }
  .nav-item.nav-messenger>img{
    width: 45%;
    padding-top: 12px;
  }
</style>
