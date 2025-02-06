<script setup lang="ts">


</script>


<template>

  <div class="main-container">

    <div class="data-container">
      <span class="lowlight">INSIGHT TO <br></span>
      <span class="highlight">EVOLVE YOUR GAME</span> <span class="lowlight"> AND</span> 
      <span class="lowlight"> AND SO MUCH <br> MORE.</span> 
    </div>

  <div class="card-container">
  <div class="card">
    <button type="button">
      <img src="../assets/cs2.webp" alt="yes" class="homeImg" > 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/league-of-legends.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/rocket-league.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/tekken8.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/cs2.webp" alt="yes" class="homeImg" > 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/league-of-legends.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/rocket-league.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/tekken8.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/cs2.webp" alt="yes" class="homeImg" > 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/league-of-legends.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/rocket-league.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
  <div class="card">
    <button type="button">
      <img src="../assets/tekken8.webp" alt="yes" class="homeImg"> 
    </button>
  </div>
</div>
</div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Rajdhani:wght@400;700&family=Roboto:wght@400;700&display=swap');

.main-container {
  display: flex;
  width: 100vw; 
  height: 100vh; 
  margin-bottom: 20%;
  gap:20px;
}

.data-container {
  flex: 1.5; 
  flex-direction: column;
  border: 1px solid black;
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  margin-left: 2%;
  background-color: #18191c;
  padding: 5px 2.5rem 2.5rem;
  top:0;
  position: sticky;
  text-align: left;
  height: 120%;
}

.card-container {
  flex: 3; 
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 10px;
  margin-bottom: 20%;
  margin-left:40px
}


.homeImg{
  width: 150px;
  height: 200px;
  object-fit: cover;
}

.lowlight{
  color:#9aa4b8;
  font-weight: 700;
  font-size: 5rem;
}

.highlight{
  background-color: #e2263c;
  color:white;
  font-weight: 700;
  font-size: 5rem;
}

.lowlight, .highlight {
  font-family: 'Rajdhani', sans-serif;
}

</style>
