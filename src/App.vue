<template>
    <!-- implememnt the router here -->
    <router-view></router-view>
  
  </template>
  
  <script>
  export default {
    name: "App",
  };
  </script>
  
  <style>
  *{
    margin:0;
    padding:0;
    box-sizing: border-box;
    /* background-color: blue; */
    
    background-size:cover;
  }
  
  body {
  /* background-image:url(assets/people.jpg);  */
  background: linear-gradient( rgba(0,0,0,0.8), rgba(0,0,0,0.7)), url(assets/people.jpg);
  background-size:cover;
  background-position: center;
  
  }
  .button
  {
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
  }
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: white;
    text-align: center;
    color: white;
    margin-top: 60px;
  
  }
  
  
  </style>
  