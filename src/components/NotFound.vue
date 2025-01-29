<script setup lang="ts">

defineProps<{ msg: string }>()


</script>

<template>
    <div>
      <h1>404 - Page non trouvée</h1>
      <p>Oups ! La page que vous recherchez n'existe pas.</p>
      <a href="#/">Retourner à l'accueil</a>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  h1 {
    color: #f44336;
  }
  a {
    color: #2196f3;
    text-decoration: none;
    font-weight: bold;
  }
  </style>
  