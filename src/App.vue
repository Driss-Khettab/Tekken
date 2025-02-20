<script setup lang="ts">
import { ref, computed } from 'vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import NotFound from './components/NotFound.vue'
import RL from './components/RL.vue'
import CS from './components/CS.vue'
import TK from './components/TK.vue'
import LOL from './components/LOL.vue'

const routes: Record<string, any> = {
  '/': Home,
  '/cs': CS,
  '/rl': RL,
  '/lol': LOL,
  '/tk': TK,
  '/about': About
}

const currentPath = ref(window.location.hash)

window.addEventListener('hashchange', () => {
  currentPath.value = window.location.hash
})

const currentView = computed(() => {
  return routes[currentPath.value.slice(1) || '/'] || NotFound
})

const backgroundClass = computed(() => {
  switch (currentPath.value) {
    case '#/cs': return 'bg-cs'
    case '#/rl': return 'bg-rl'
    case '#/lol': return 'bg-lol'
    case '#/tk': return 'bg-tk'
    case '#/about': return 'bg-about'
    default: return 'bg-default'
  }
})
</script>

<template>
  <div class="nav-bar">
    <a class="link" href="#/">Home</a> |
    <a class="link" href="#/cs">Counter Strike</a> |
    <a class="link" href="#/rl">Rocket League</a> |
    <a class="link" href="#/lol">League Of Legends</a> |
    <a class="link" href="#/tk">Tekken</a> |
    <a class="link" href="#/about">About</a> |
  </div>

  <div class="page-container" :class="backgroundClass">
    <component :is="currentView" />
  </div>
</template>

<style scoped>
.page-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  min-height: 100vh;
  padding-top: 12vh;
  transition: background-color 0.5s ease-in-out;
}

.bg-default {
  background-color: #060708;
}

.bg-cs {
  background-color: #2a2a2a;
}

.bg-rl {
  background-color: #1d3557;
}

.bg-lol {
  background: linear-gradient(to right, #391618, #961929);
}

.bg-tk {
  background-color: #b71c1c;
}

.bg-about {
  background-color: #004d40;
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

.link {
  color: black;
}
</style>
