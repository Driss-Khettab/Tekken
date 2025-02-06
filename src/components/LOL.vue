<script setup lang="ts">

defineProps<{ msg: string }>()


</script>

<template>
    <div class="main">
      <div class="svg">
         <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="title-icon"><path d="M5.6 2a.46.46 0 0 0-.4.5.37.37 0 0 0 .1.3l1.3 1.7v15.2l-1.7 1.7a.377.377 0 0 0 .1.6h13.4a.76.76 0 0 0 .4-.2l2.3-2.3a.377.377 0 0 0-.1-.6.37.37 0 0 0-.3-.1h-9.5V2.5a.472.472 0 0 0-.5-.5ZM12 3.8v.9a8.237 8.237 0 0 1 8.2 8.2 7.96 7.96 0 0 1-1.7 5h1.1a8.9 8.9 0 0 0 1.5-5A9.133 9.133 0 0 0 12 3.8m0 1.8v12.3h5.3a7.48 7.48 0 0 0 2-5A7.34 7.34 0 0 0 12 5.6m-6.4.8a9.52 9.52 0 0 0-2.7 6v1.3a9.27 9.27 0 0 0 2.7 5.7V18a8.15 8.15 0 0 1-1.8-5.1 7.75 7.75 0 0 1 1.8-5.1zm0 3a7.3 7.3 0 0 0-.9 3.5 6.76 6.76 0 0 0 .9 3.5z"></path></svg>
      </div>
      <div class="text">
      <h1>LEAGUE OF LEGENDS STAT</h1>
      <p>Check Detailed League of Legends Stats and Leaderboards</p>
      </div>
      <div>
        <svg data-v-c97a4dd3="" data-v-980db306="" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" version="1.0" viewBox="0 0 150 150" class="platform-icon platform-riot icon"><path d="M80.115 8.324 0 45.356l19.96 75.96 15.265-1.897-4.245-47.69 5.058-2.258 8.58 48.774 25.923-3.162-4.607-52.657 4.878-2.167 9.483 53.65 26.284-3.251-5.058-57.715 4.967-2.168 10.387 58.618 25.922-3.161V24.04zM82.011 123.393l1.265 7.497 59.521 9.935v-24.838l-60.695 7.406z"></path></svg>
        <input>
      </div>
    </div>
  </template>
  

  
  <script setup>
  </script>
  
  <style scoped>
  .main{
    background-color: white;
    display: flex;
  }



  .svg{
    background-color: #c79c58;
    border-radius: 0.25rem;
    height: 4rem;
    width: 4rem;
    padding: 0.75rem;
  }

  .title-icon{
    height: 2.5rem;
    width: 2.5rem;
    margin-top:0.25rem ;
  }

  h1 {
    color: #4caf50;
  }
  </style>
  