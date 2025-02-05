<script setup lang="ts">
import { ref, computed } from 'vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import NotFound from './components/NotFound.vue'
import RL from './components/RL.vue';
import CS from './components/CS.vue'
import TK from './components/TK.vue'

const routes: Record<string, any> =  {
  '/': Home,
  '/cs': CS,
  '/rl' : RL,
  '/tk' : TK,
  '/about': About
}

const currentPath = ref(window.location.hash)

window.addEventListener('hashchange', () => {
  currentPath.value = window.location.hash
})

const currentView = computed(() => {
  return routes[currentPath.value.slice(1) || '/'] || NotFound
})
</script>

<template>
  <div class="nav-bar">
    <a class="link" href="#/">Home</a> |
    <a class="link" href="#/cs">Counter Strike</a> |
    <a class="link" href="#/rl">Rocket League</a> |
    <a class="link" href="#/tk">Tekken</a> |
    <a class="link" href="#/about">About</a> |
    <a class="link" href="#/non-existent-path">Broken Link</a>
  </div>

  <div class="page-container">
    <component :is="currentView" />
  </div>
</template>


<style scoped>
.page-container {
  /* background-image: url('./assets/TrackerBG.webp'); 
  background-size: cover;
  background-position: center; 
  background-repeat: no-repeat;  */
  background-color: #060708;
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  min-height: 100vh;
  padding-top: 12vh;
}


.nav-bar {
  position: fixed;
  top: 2%;
  left: 50%;
  transform: translateX(-50%);
  width: 40%;
  max-width: 800px;
  height: 5vh;
  background: rgba(255, 255, 255, 0.9);
  border: 1px solid black;
  border-radius: 25px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 1%;
  z-index: 1000;
}

.link{
  color: black;
}

</style>
