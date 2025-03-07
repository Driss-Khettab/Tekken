<script setup lang="ts">

defineProps<{ msg: string }>()


</script>

<template>
  <div class="main">

    <div class="logo-title">
      <div class="title-svg">
      <div class="svg">
        <svg data-v-a7720650="" viewBox="0 0 24 24" class="title-icon"><rect width="100%" height="100%" style="fill: none;"></rect><path d="m3.9 11.5-.7-.3h4.9c.2 0 .4-.1.5-.3l.4-1H4.3c-.8 0-1.5.5-1.9 1.2l-1.3 3.1c-.3.7.2 1.4.9 1.4h4.3c.2 0 .4-.1.5-.3l.4-1H2.7zM17.8 9.9c-.8 0-1.5.5-1.9 1.2l-.2.5-.1.4c-.3.7.2 1.4.9 1.4h3.4l-.4.9h-4.6c-.2 0-.4.1-.5.3l-.4 1h5.2c.8 0 1.5-.5 1.9-1.2l.4-.9c.3-.7-.2-1.4-.9-1.4h-3.4l.2-.6-.6-.3h5.4c.2 0 .4-.1.5-.3l.4-1zM14.6 10l-.1-.6.1-.1.1-.3h1.4v-.2h.6v-.2h-.6v-.30000000000000004l-.1.1h-2.5.1V8h-.1c0-.1-.1-.5-.8-.6-.3 0-.5.1-.6.2 0 0-.1.1-.1.2v.6000000000000001l.1.1-.1.1h-.2c-.2 0-.5.2-.7.7s-.3.6-.3.6h-.2l-.3 1 .2.2-.1.4-.2.1-.2.6h-.3s-.1 0-.1.1l-.1.9-.1.3-.2.2c0 .2-.1.3-.2.4l-.7 1.5v.1l.1.1v.2l-.4.5v.1h.7l.1-.1v-.6l1.4-1.6s.1-.1.1-.2l.7-1.5h.1c.1.1.2.3.3.4s.3.5.4.6c0 0 .1.1.2.1l-.4.7-.2.8v.7999999999999999c0 .1-.1.1-.1.2l-.1.4h1.1c.1 0 .2 0 .3-.1h.1l.1-.1-.5-.1s-.1 0-.1-.1l-.1-.2.2-.2.7-1.7v-.4c0-.1-.3-.5-.3-.6-.1-.1-.4-.7-.5-.9v-.4h.1l.4-.8-.1-.1.1-.1.4.2h.1c.1 0 .3-.1.4-.1l.1-.1.3-.9v.2z"></path></svg>
         </div>
      <div class="text">
      <h1 class="h1-title">CS2 STATS</h1>
      <p class="subtitle">Check Detailed CS2 Stats and Leaderboards</p>
      </div>
    </div>

      <div class="input">
        <div class="svg-input">
        <svg data-v-c97a4dd3="" data-v-980db306="" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="platform-icon-steam"><path d="M12 0a12 12 0 0 1 12 12 12 12 0 0 1-12 12C6.48 24 1.86 20.304.432 15.276l4.596 1.896a3.41 3.41 0 0 0 3.336 2.724A3.4 3.4 0 0 0 11.76 16.5v-.156l4.08-2.916h.096a4.527 4.527 0 0 0 4.524-4.524 4.527 4.527 0 0 0-4.524-4.524c-2.496 0-4.536 2.028-4.536 4.524v.06l-2.844 4.152-.192-.012c-.708 0-1.368.216-1.908.588L0 11.04C.516 4.86 5.676 0 12 0M7.536 18.204a1.88 1.88 0 0 0 2.46-1.008A1.88 1.88 0 0 0 9 14.748l-1.536-.636a2.53 2.53 0 0 1 1.872.036 2.44 2.44 0 0 1 1.38 1.38c.264.624.264 1.32 0 1.944-.516 1.296-2.04 1.92-3.336 1.38a2.5 2.5 0 0 1-1.308-1.248zm11.424-9.3a3.027 3.027 0 0 1-3.024 3.024 3.024 3.024 0 0 1-3.012-3.024 3 3 0 0 1 3.012-3.012 3.024 3.024 0 0 1 3.024 3.012m-5.28 0a2.266 2.266 0 0 0 2.268 2.268 2.264 2.264 0 0 0 2.256-2.268 2.264 2.264 0 0 0-2.256-2.268 2.266 2.266 0 0 0-2.268 2.268"></path></svg>        </div>
        <input class="input-id"
        placeholder="Enter Steam ID, URL or Vanity">
      </div>

    <div class="riot-signin">
      <div class="search-box-container">
        <div class="search-box__or">
          "or"
        </div>
      </div>  
      </div>

      <div class="searchbox__signin">
        <svg data-v-c97a4dd3="" data-v-980db306="" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="platform-icon platform-steam icon"><path d="M12 0a12 12 0 0 1 12 12 12 12 0 0 1-12 12C6.48 24 1.86 20.304.432 15.276l4.596 1.896a3.41 3.41 0 0 0 3.336 2.724A3.4 3.4 0 0 0 11.76 16.5v-.156l4.08-2.916h.096a4.527 4.527 0 0 0 4.524-4.524 4.527 4.527 0 0 0-4.524-4.524c-2.496 0-4.536 2.028-4.536 4.524v.06l-2.844 4.152-.192-.012c-.708 0-1.368.216-1.908.588L0 11.04C.516 4.86 5.676 0 12 0M7.536 18.204a1.88 1.88 0 0 0 2.46-1.008A1.88 1.88 0 0 0 9 14.748l-1.536-.636a2.53 2.53 0 0 1 1.872.036 2.44 2.44 0 0 1 1.38 1.38c.264.624.264 1.32 0 1.944-.516 1.296-2.04 1.92-3.336 1.38a2.5 2.5 0 0 1-1.308-1.248zm11.424-9.3a3.027 3.027 0 0 1-3.024 3.024 3.024 3.024 0 0 1-3.012-3.024 3 3 0 0 1 3.012-3.012 3.024 3.024 0 0 1 3.024 3.012m-5.28 0a2.266 2.266 0 0 0 2.268 2.268 2.264 2.264 0 0 0 2.256-2.268 2.264 2.264 0 0 0-2.256-2.268 2.266 2.266 0 0 0-2.268 2.268"></path></svg>
        <span class="sign-in_description">Sign in with Steam</span>
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
          <p class="name">Spotlight</p>
          <h1 class="value">#1</h1>
        </div>
        <div class="player1">
          <p class="leader-card">#1</p>
          <div class="avatar-container">
          <img src="../assets/pp.webp" alt="profile-picture-euWest" class="user-avatar">
        </div>
        <div class="username">
          <h2>J1HUIV</h2>
        </div>
          <p class="name">Spotlight</p>
          <h1 class="value">#2</h1>
        </div>
        <div class="player1">
          <p class="leader-card">#1</p>
          <div class="avatar-container">
          <img src="../assets/pp.webp" alt="profile-picture-euWest" class="user-avatar">
        </div>
        <div class="username">
          <h2>J1HUIV</h2>
        </div>
          <p class="name">Spotlight</p>
          <h1 class="value">#3</h1>
        </div>
      </div>
  </div>
  <section class="checkpoint_news">
  <div class="section-container">
    <div class="checkpoint_intro">
      <div class="checkpoint_title">
      <svg data-v-a7720650="" viewBox="0 0 24 24" class="checkpoint__title-icon"><rect width="100%" height="100%" style="fill: none;"></rect><path d="m3.9 11.5-.7-.3h4.9c.2 0 .4-.1.5-.3l.4-1H4.3c-.8 0-1.5.5-1.9 1.2l-1.3 3.1c-.3.7.2 1.4.9 1.4h4.3c.2 0 .4-.1.5-.3l.4-1H2.7zM17.8 9.9c-.8 0-1.5.5-1.9 1.2l-.2.5-.1.4c-.3.7.2 1.4.9 1.4h3.4l-.4.9h-4.6c-.2 0-.4.1-.5.3l-.4 1h5.2c.8 0 1.5-.5 1.9-1.2l.4-.9c.3-.7-.2-1.4-.9-1.4h-3.4l.2-.6-.6-.3h5.4c.2 0 .4-.1.5-.3l.4-1zM14.6 10l-.1-.6.1-.1.1-.3h1.4v-.2h.6v-.2h-.6v-.30000000000000004l-.1.1h-2.5.1V8h-.1c0-.1-.1-.5-.8-.6-.3 0-.5.1-.6.2 0 0-.1.1-.1.2v.6000000000000001l.1.1-.1.1h-.2c-.2 0-.5.2-.7.7s-.3.6-.3.6h-.2l-.3 1 .2.2-.1.4-.2.1-.2.6h-.3s-.1 0-.1.1l-.1.9-.1.3-.2.2c0 .2-.1.3-.2.4l-.7 1.5v.1l.1.1v.2l-.4.5v.1h.7l.1-.1v-.6l1.4-1.6s.1-.1.1-.2l.7-1.5h.1c.1.1.2.3.3.4s.3.5.4.6c0 0 .1.1.2.1l-.4.7-.2.8v.7999999999999999c0 .1-.1.1-.1.2l-.1.4h1.1c.1 0 .2 0 .3-.1h.1l.1-.1-.5-.1s-.1 0-.1-.1l-.1-.2.2-.2.7-1.7v-.4c0-.1-.3-.5-.3-.6-.1-.1-.4-.7-.5-.9v-.4h.1l.4-.8-.1-.1.1-.1.4.2h.1c.1 0 .3-.1.4-.1l.1-.1.3-.9v.2z"></path></svg>        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 109.196 13.286" class="checkpoint__title-logo"><path d="M0 10.629V2.657A2.324 2.324 0 0 1 2.657 0h4.4a2.324 2.324 0 0 1 2.657 2.657v2.164H6.981V2.885c0-.285-.095-.38-.379-.38H3.113c-.285 0-.38.1-.38.38v7.516c0 .285.095.379.38.379h3.492c.285 0 .379-.095.379-.379V8.465h2.733v2.164a2.324 2.324 0 0 1-2.657 2.657h-4.4a2.324 2.324 0 0 1-2.657-2.657M11.673.001h2.733v5.238h4.707V.001h2.733v13.285h-2.733V7.744h-4.707v5.542h-2.733Zm12.698 0h8.94v2.5h-6.206v2.752h5.03V7.72h-5.03v3.056h6.206v2.505h-8.94Zm10.402 10.628V2.657A2.324 2.324 0 0 1 37.43 0h4.4a2.324 2.324 0 0 1 2.657 2.657v2.164h-2.733V2.885c0-.285-.095-.38-.38-.38h-3.492c-.285 0-.38.1-.38.38v7.516c0 .285.095.379.38.379h3.492c.285 0 .38-.095.38-.379V8.465h2.733v2.164a2.324 2.324 0 0 1-2.657 2.657h-4.4a2.324 2.324 0 0 1-2.657-2.657m19.435 2.657-3.132-5.751-1.936 2.449v3.3h-2.7V.002h2.7v6.226L53.866.002h3.208l-4.157 5.239 4.365 8.048ZM58.479.002h7.019a2.324 2.324 0 0 1 2.657 2.657v3.53a2.324 2.324 0 0 1-2.657 2.656h-4.289v4.441h-2.733Zm6.567 6.339c.285 0 .38-.1.38-.38V2.885c0-.285-.095-.38-.38-.38h-3.834v3.834Zm4.518 4.288V2.657A2.324 2.324 0 0 1 72.221 0h4.878a2.324 2.324 0 0 1 2.657 2.657v7.972a2.324 2.324 0 0 1-2.657 2.657h-4.878a2.324 2.324 0 0 1-2.657-2.657m7.08.152c.285 0 .38-.095.38-.379V2.885c0-.285-.095-.38-.38-.38h-3.967c-.285 0-.38.1-.38.38v7.516c0 .285.095.379.38.379ZM81.959 0h2.733v13.286h-2.733zm5.257.001h2.847l5.03 8.56V.001h2.657v13.285h-2.657l-5.219-8.864v8.864h-2.657Zm15.641 2.466h-3.606V.001h9.946v2.467h-3.606v10.818h-2.733Z"></path></svg>
      </div>
      <p class="checkpoint_description">CS2 and Tracker news, updates and more </p>
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
    gap: 10px;
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
    background-color: #f29224;
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
    text-align: left;
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

.sign-in_description{
  color: white;
  margin-left: 20px;
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
  background-color: rgb(93, 131, 41);
  padding: 0.5rem;
  width: 67%;
}

.platform-icon{
  width: 1rem;
  height: 1rem;
  fill: white;
}

.platform-icon-steam{
  width: 1rem;
  height: 1rem;
  fill: white;
  margin-top: 10px;
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

.checkpoint_description{
  color: white;
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
  color: white;
}

.trk-button__icon{
  display: block;
  height: 1.5rem;
  width: 1.5rem;
  margin: -.25rem 0 -.25rem;
  fill: white;
}
  </style>
  