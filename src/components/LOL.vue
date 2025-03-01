<script setup lang="ts">

defineProps<{ msg: string }>()


</script>

<template>
  <div class="main">

    <div class="logo-title">
      <div class="title-svg">
      <div class="svg">
         <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="title-icon"><path d="M5.6 2a.46.46 0 0 0-.4.5.37.37 0 0 0 .1.3l1.3 1.7v15.2l-1.7 1.7a.377.377 0 0 0 .1.6h13.4a.76.76 0 0 0 .4-.2l2.3-2.3a.377.377 0 0 0-.1-.6.37.37 0 0 0-.3-.1h-9.5V2.5a.472.472 0 0 0-.5-.5ZM12 3.8v.9a8.237 8.237 0 0 1 8.2 8.2 7.96 7.96 0 0 1-1.7 5h1.1a8.9 8.9 0 0 0 1.5-5A9.133 9.133 0 0 0 12 3.8m0 1.8v12.3h5.3a7.48 7.48 0 0 0 2-5A7.34 7.34 0 0 0 12 5.6m-6.4.8a9.52 9.52 0 0 0-2.7 6v1.3a9.27 9.27 0 0 0 2.7 5.7V18a8.15 8.15 0 0 1-1.8-5.1 7.75 7.75 0 0 1 1.8-5.1zm0 3a7.3 7.3 0 0 0-.9 3.5 6.76 6.76 0 0 0 .9 3.5z"></path></svg>
      </div>
      <div class="text">
      <h1 class="h1-title">LEAGUE OF LEGENDS STATS</h1>
      <p class="subtitle">Check Detailed League of Legends Stats and Leaderboards</p>
      </div>
    </div>

      <div class="input">
        <div class="svg-input">
           <svg  data-v-980db306="" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" version="1.0" viewBox="0 0 150 150" class="input-icon"><path d="M80.115 8.324 0 45.356l19.96 75.96 15.265-1.897-4.245-47.69 5.058-2.258 8.58 48.774 25.923-3.162-4.607-52.657 4.878-2.167 9.483 53.65 26.284-3.251-5.058-57.715 4.967-2.168 10.387 58.618 25.922-3.161V24.04zM82.011 123.393l1.265 7.497 59.521 9.935v-24.838l-60.695 7.406z"></path></svg>
        </div>
        <input class="input-id"
        placeholder="Enter Riot ID, ie. player#NA1">
      </div>

    <div class="riot-signin">
      <div class="search-box-container">
        <div class="search-box__or">
          "or"
        </div>
      </div>  
      </div>

      <div class="searchbox__signin">
        <svg  xmlns="http://www.w3.org/2000/svg" xml:space="preserve" version="1.0" viewBox="0 0 150 150" class="platform-icon"><path d="M80.115 8.324 0 45.356l19.96 75.96 15.265-1.897-4.245-47.69 5.058-2.258 8.58 48.774 25.923-3.162-4.607-52.657 4.878-2.167 9.483 53.65 26.284-3.251-5.058-57.715 4.967-2.168 10.387 58.618 25.922-3.161V24.04zM82.011 123.393l1.265 7.497 59.521 9.935v-24.838l-60.695 7.406z"></path></svg>
        <span>Sign in with Riot ID</span>
      </div>

    </div>

    <div class="leaderboard">
        <div class="player1">
          <p class="leader-card">#1</p>
          <div class="avatar-container">
          <img src="../assets/pp.webp" alt="profile-picture-euWest" class="user-avatar">
        </div>
        <div class="username">
          <h2>J1HUIV</h2>
        </div>
          <p class="name">League Points</p>
          <h1 class="value">2 005</h1>
          <p>EU West</p>
        </div>
        <div class="player1">
          <p class="leader-card">#1</p>
          <div class="avatar-container">
          <img src="../assets/pp.webp" alt="profile-picture-euWest" class="user-avatar">
        </div>
        <div class="username">
          <h2>J1HUIV</h2>
        </div>
          <p class="name">League Points</p>
          <h1 class="value">2 005</h1>
          <p>EU West</p>
        </div>
        <div class="player1">
          <p class="leader-card">#1</p>
          <div class="avatar-container">
          <img src="../assets/pp.webp" alt="profile-picture-euWest" class="user-avatar">
        </div>
        <div class="username">
          <h2>J1HUIV</h2>
        </div>
          <p class="name">League Points</p>
          <h1 class="value">2 005</h1>
          <p>EU West</p>
        </div>
      </div>
  </div>
  <section class="checkpoint_news">
  <div class="section-container">
    <div class="checkpoint_intro">
      <div class="checkpoint_title">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="checkpoint__title-icon"><path d="M5.6 2a.46.46 0 0 0-.4.5.37.37 0 0 0 .1.3l1.3 1.7v15.2l-1.7 1.7a.377.377 0 0 0 .1.6h13.4a.76.76 0 0 0 .4-.2l2.3-2.3a.377.377 0 0 0-.1-.6.37.37 0 0 0-.3-.1h-9.5V2.5a.472.472 0 0 0-.5-.5ZM12 3.8v.9a8.237 8.237 0 0 1 8.2 8.2 7.96 7.96 0 0 1-1.7 5h1.1a8.9 8.9 0 0 0 1.5-5A9.133 9.133 0 0 0 12 3.8m0 1.8v12.3h5.3a7.48 7.48 0 0 0 2-5A7.34 7.34 0 0 0 12 5.6m-6.4.8a9.52 9.52 0 0 0-2.7 6v1.3a9.27 9.27 0 0 0 2.7 5.7V18a8.15 8.15 0 0 1-1.8-5.1 7.75 7.75 0 0 1 1.8-5.1zm0 3a7.3 7.3 0 0 0-.9 3.5 6.76 6.76 0 0 0 .9 3.5z"></path></svg>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 109.196 13.286" class="checkpoint__title-logo"><path d="M0 10.629V2.657A2.324 2.324 0 0 1 2.657 0h4.4a2.324 2.324 0 0 1 2.657 2.657v2.164H6.981V2.885c0-.285-.095-.38-.379-.38H3.113c-.285 0-.38.1-.38.38v7.516c0 .285.095.379.38.379h3.492c.285 0 .379-.095.379-.379V8.465h2.733v2.164a2.324 2.324 0 0 1-2.657 2.657h-4.4a2.324 2.324 0 0 1-2.657-2.657M11.673.001h2.733v5.238h4.707V.001h2.733v13.285h-2.733V7.744h-4.707v5.542h-2.733Zm12.698 0h8.94v2.5h-6.206v2.752h5.03V7.72h-5.03v3.056h6.206v2.505h-8.94Zm10.402 10.628V2.657A2.324 2.324 0 0 1 37.43 0h4.4a2.324 2.324 0 0 1 2.657 2.657v2.164h-2.733V2.885c0-.285-.095-.38-.38-.38h-3.492c-.285 0-.38.1-.38.38v7.516c0 .285.095.379.38.379h3.492c.285 0 .38-.095.38-.379V8.465h2.733v2.164a2.324 2.324 0 0 1-2.657 2.657h-4.4a2.324 2.324 0 0 1-2.657-2.657m19.435 2.657-3.132-5.751-1.936 2.449v3.3h-2.7V.002h2.7v6.226L53.866.002h3.208l-4.157 5.239 4.365 8.048ZM58.479.002h7.019a2.324 2.324 0 0 1 2.657 2.657v3.53a2.324 2.324 0 0 1-2.657 2.656h-4.289v4.441h-2.733Zm6.567 6.339c.285 0 .38-.1.38-.38V2.885c0-.285-.095-.38-.38-.38h-3.834v3.834Zm4.518 4.288V2.657A2.324 2.324 0 0 1 72.221 0h4.878a2.324 2.324 0 0 1 2.657 2.657v7.972a2.324 2.324 0 0 1-2.657 2.657h-4.878a2.324 2.324 0 0 1-2.657-2.657m7.08.152c.285 0 .38-.095.38-.379V2.885c0-.285-.095-.38-.38-.38h-3.967c-.285 0-.38.1-.38.38v7.516c0 .285.095.379.38.379ZM81.959 0h2.733v13.286h-2.733zm5.257.001h2.847l5.03 8.56V.001h2.657v13.285h-2.657l-5.219-8.864v8.864h-2.657Zm15.641 2.466h-3.606V.001h9.946v2.467h-3.606v10.818h-2.733Z"></path></svg>
      </div>
      <p class="checkpoint_description">LoL and Traker news, updates and more </p>
    </div>

    <div class="checkpoint_articles">
      <article class="checkpoint-tile" title="Claim Your Drattak Avatar Frame">
        <a class="a-checkpoint-tile" href="">
          <img class="checkpoint-tile_image" src="../assets/claim.webp" alt="">
          <div class="checkpoint-tile_info">
            <h2 class="checkpoint-tile_tittle">Claim Your Drattak Avatar Frame
            </h2>
            <span class="checkpoint-tile_timeago">3w ago</span>
          </div>
        </a>
      </article>

      <article class="checkpoint-tile" title="Claim Your Drattak Avatar Frame">
        <a class="a-checkpoint-tile" href="">
          <img class="checkpoint-tile_image" src="../assets/claim.webp" alt="">
          <div class="checkpoint-tile_info">
            <h2 class="checkpoint-tile_tittle">Claim Your Drattak Avatar Frame
            </h2>
            <span class="checkpoint-tile_timeago">3w ago</span>
          </div>
        </a>
      </article>

      <article class="checkpoint-tile" title="Claim Your Drattak Avatar Frame">
        <a class="a-checkpoint-tile" href="">
          <img class="checkpoint-tile_image" src="../assets/claim.webp" alt="">
          <div class="checkpoint-tile_info">
            <h2 class="checkpoint-tile_tittle">Claim Your Drattak Avatar Frame
            </h2>
            <span class="checkpoint-tile_timeago">3w ago</span>
          </div>
        </a>
      </article>
    </div>


    <a class="trk-button">
       View All 
      <svg  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="trk-button__icon"><path d="m12 4-1.41 1.41L16.17 11H4v2h12.17l-5.58 5.59L12 20l8-8Z"></path></svg>
    </a>
  </div>
</section>

  </template>
  

  
  <script setup>
  </script>
  
  <style scoped>

  .main{
    display: flex;
    background-image: url(../assets/534862.webp);
    background-size: cover;
    background-position: 50%;
    border-bottom-left-radius: 10rem;
  }



  .logo-title{
    display: flex;
    flex: 1;
    flex-direction: column;
    height: 70vh;
    
  }

  .title-svg{
    display: flex;
    flex-direction: row;
    margin-left: 10%;
    margin-top: 5%;
  }

  .leaderboard{
    display: flex;
    flex:1;
    gap : 1%
  }

  .text{
    display: flex;
    flex-direction: column;
  }

  .svg{
    background-color: #c79c58;
    border-radius: 0.25rem;
    height: 2.5rem;
    width: 2.5rem;
    padding: 0.75rem;
  }

  .svg-input{
    background-color: #202026;
    border-radius: 0.25rem;
    height: 2.5rem;
    width: 2.5rem;
    padding: 0.75rem;
  }

  .title-icon{
    height: 2.5rem;
    width: 2.5rem;
    margin-top:0.25rem ;
  }

  .h1-title{
    font-size: 2rem;
    color: white;
    margin-top: .50rem;
    line-height: 2rem;
  }

  .subtitle{
    font-size: 1rem;
    margin-top: -20px;
    color: #bfb6b6;
  }

  .input{
    display: flex;
    margin-left: 10%;
  }

  .input-id{
    height: 3.5rem;
    width: 65%;
  }
  
  .input-icon{
    height: 2.5rem;
    width: 2.5rem;
    margin-top:0.25rem ;
    background-color: #202026;
    fill: white;
  }

  .player1{
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    width: 10rem;
    height: 50%;
    margin-top: 10%;
    background-color: #2f2f38;
    /* border: 2px solid black; */
    color: white;
    border-radius: 10%;
  }

  .leader-card{
    color:#111;
    border: 1px solid black;
    width: 2.5rem;
    height: 2.5rem;
    /* padding: .5rem; */
    position: absolute;
    top:0;
    right: 0;
    margin: 0;
    border-bottom-left-radius: 1.5rem;
    background: #cbb765;
  }

  .avatar-container{
    background: linear-gradient(to bottom, #202026, transparent);
    border-radius: 50%;
    width: 4.5rem;
    height: 4.5rem;
    margin: .5rem .5rem 0;
    padding: .5rem;
    position: relative;
  }

  .user-avatar{
    border-radius: 50%;
    border-style: solid;
    width: 4.5rem;
    height: 4.5rem;
  }

  .user-avatar--borderless{
    box-shadow: inset 0 0 0 .125rem #cbb765;
  }

  .username{
    display: flex;
    align-items: center;
    font-size:1.125rem;
    font-weight: 700;
  }

  .player1 h2,
  .player1 h1,
  .player1 p {
    margin: 0.2rem 0; 
    line-height: 1.2;
}

.name {
  color:#cbb765;
  font-size: .75rem;
  font-weight: 500;
}

.value{
  font-size: 2rem;
  font-weight: 700;
}

.search-box-container {
  display: flex;
  justify-content: center;
  width: 100%; /* Prend toute la largeur de .logo-title */
}

.search-box__or{
  display: flex;
  -webkit-box-align: center;
  align-items: center;
  justify-content: center;
  color: #ffffffd9;
  width: 50%; /* Ajuste à la largeur souhaitée */
  max-width: 400px; /* Évite que ce soit trop large */
}

.search-box__or::before,
.search-box__or::after {
  content: "";
  flex: 1; 
  width: fit-content;
  height: 1px; 
  background-color: #ffffffd9; 
} 

.search-box__or::before {
  margin-right: 10px;
}

.search-box__or::after {
  margin-left: 10px;
}

.searchbox__signin{
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  margin-top: 1.5rem;
  margin-left: 10%;
  background-color: rgb(213, 52, 53);
  padding: 0.5rem;
  width: 67%;
}

.platform-icon{
  width: 1rem;
  height: 1rem;
  fill: white;
}



.checkpoint_articles{
  display: grid;
  gap: 1rem;
  grid-template-columns: repeat(3, 1fr);
}

.checkpoint_news{ 
  padding: 1.5rem;
}

.section-container{
  display: flex;
  gap: 2rem;
  justify-content: space-between;
}

.checkpoint_intro{
  max-width: 10rem;
}

.checkpoint_title{
  display: flex;
  align-items: center;
  gap: .5rem;
  margin-bottom: .5rem;
}

.checkpoint__title-icon{
  width: 1.5rem;
  height: 1.5rem; 
  padding: .25rem;
  background-color: #c79c58;
}

.checkpoint__title-logo{
  height: .8125rem;
  fill: white;
}

.checkpoint_description{
  margin: 0;
}

.checkpoint-tile{
  display: flex;
  flex-direction: row-reverse; /* Inverse l'ordre des enfants */
  align-items: center; /* Aligne verticalement */
  gap: 1rem;
}

.checkpoint-tile_info {
  flex: 1; /* Permet au texte de prendre le reste de l'espace */
}

.checkpoint-tile_tittle{
  font-size: .875rem;
  font-weight: 500;
  line-height: 1rem;
  word-wrap: break-word;
  width: 150px;
  color: white;

}

.checkpoint-tile_timeago{
  font-size: .625rem;
  font-weight: 500;
  opacity: .5;
  color: white;
}

.a-checkpoint-tile{
  display: flex;
}

.trk-button{
  display: flex;
  background-color: #ffffff26;
  gap:.5rem;
  margin: .25rem .25rem;
  color: inherit;
  align-items: center;
  justify-content: center;
  padding: 1rem 1.5rem;
}

.trk-button__icon{
  display: block;
  height: 1.5rem;
  width: 1.5rem;
  margin: -.25rem 0 -.25rem;
  fill: white;
}
  </style>
  