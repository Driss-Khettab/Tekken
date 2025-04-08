<script setup lang="ts"></script>

<template>
  <div class="main">
    <div class="container"></div>
    <header class="header">
      <div class="banner">
        <img src="../assets/csbanneer.webp" alt="cs-banner" class="banner" />

        <div class="player-info">
          <div class="avatar-container-pos">
            <div class="avatar-container">
              <img src="../assets/cs2.webp" class="user-avatar" />
            </div>
          </div>

          <div class="view">
            <div class="view-info">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 18 18"
                class="view-svg"
              >
                <path
                  fill="currentColor"
                  d="M9 3.375C5.25 3.375 2.047 5.707.75 9c1.297 3.293 4.5 5.625 8.25 5.625S15.953 12.293 17.25 9C15.953 5.707 12.75 3.375 9 3.375m0 9.375c-2.07 0-3.75-1.68-3.75-3.75S6.93 5.25 9 5.25 12.75 6.93 12.75 9 11.07 12.75 9 12.75m0-6A2.247 2.247 0 0 0 6.75 9 2.247 2.247 0 0 0 9 11.25 2.247 2.247 0 0 0 11.25 9 2.247 2.247 0 0 0 9 6.75"
                  opacity=".75"
                ></path>
              </svg>
              <span> 13 585 Views</span>
            </div>

            <div class="username-container">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                class="platform-icon"
              >
                <path
                  d="M12 0a12 12 0 0 1 12 12 12 12 0 0 1-12 12C6.48 24 1.86 20.304.432 15.276l4.596 1.896a3.41 3.41 0 0 0 3.336 2.724A3.4 3.4 0 0 0 11.76 16.5v-.156l4.08-2.916h.096a4.527 4.527 0 0 0 4.524-4.524 4.527 4.527 0 0 0-4.524-4.524c-2.496 0-4.536 2.028-4.536 4.524v.06l-2.844 4.152-.192-.012c-.708 0-1.368.216-1.908.588L0 11.04C.516 4.86 5.676 0 12 0M7.536 18.204a1.88 1.88 0 0 0 2.46-1.008A1.88 1.88 0 0 0 9 14.748l-1.536-.636a2.53 2.53 0 0 1 1.872.036 2.44 2.44 0 0 1 1.38 1.38c.264.624.264 1.32 0 1.944-.516 1.296-2.04 1.92-3.336 1.38a2.5 2.5 0 0 1-1.308-1.248zm11.424-9.3a3.027 3.027 0 0 1-3.024 3.024 3.024 3.024 0 0 1-3.012-3.024 3 3 0 0 1 3.012-3.012 3.024 3.024 0 0 1 3.024 3.012m-5.28 0a2.266 2.266 0 0 0 2.268 2.268 2.264 2.264 0 0 0 2.256-2.268 2.264 2.264 0 0 0-2.256-2.268 2.266 2.266 0 0 0-2.268 2.268"
                ></path>
              </svg>
              <span class="username">ketazu</span>
            </div>
          </div>
        </div>

        <div class="tabs">
          <a class="tabs-description">Overview</a>
          <a class="tabs-description">Matches</a>
          <a class="tabs-description">Maps</a>
          <a class="tabs-description">Weapons</a>
        </div>
      </div>
    </header>

    <div class="content">

      <div class="side-card">
        <table class="maps">
          <thead>
            <tr>
              <th class="table-th">Map</th>
              <th class="table-th">Rating</th>
              <th class="table-th">Win %</th>
            </tr>
          </thead>
          <tbody>
            <tr class="d2">
              <td><div>Dust 2</div></td>
              <td><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td><div>50.0%</div><div>146W - 114L</div></td>
            </tr>
            <tr class="vertigo">
              <td class="table_column--left"><div>Vertigo</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="mirage">
              <td class="table_column--left"><div>Mirage</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="ancient">
              <td class="table_column--left"><div>Ancient</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="nuke">
              <td class="table_column--left"><div>Nuke</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="inferno">
              <td class="table_column--left"><div>Inferno</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="overpass">
              <td class="table_column--left"><div>Overpass</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="train">
              <td class="table_column--left"><div>Train</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
            <tr class="anubis">
              <td class="table_column--left"><div>Anubis</div></td>
              <td class="table_column--center"><div><img src="../assets/skillgroup15.webp" class="rank-image"></div></td>
              <td class="table_column--right"><div>--%</div><div>--W - --L</div></td>
            </tr>
          </tbody>
        </table> 
        <div class="faceit">
          <header>
            <div></div>
          </header>
          <div>
            <h2>FACEIT Stats</h2>
            <div></div>
          </div>
        </div>
      </div>

      <div class="main-content">
      <div class="competitive-overview"></div>

      <div class="side-data">
        <div class="t-side"></div>
        <div class="ct-side"></div>
      </div>

      <div class="match-history"></div>
      </div> 
    </div>

  </div>
</template>

<style scoped>
.main {
  display: flex;
  flex-direction: column;
}

.container {
  container-name: site;
  container-type: inline-size;
  margin-left: auto;
  margin-right: auto;
  max-width: 1400px;
  padding-left: 0.25rem;
  padding-right: 0.25rem;
  position: relative;
  width: 100%;
  height: 100%;
}

.header {
  display: flex;
  flex-direction: column;
  min-height: 20rem;
}

.banner {
  position: relative;
  border-radius: 1rem;
}

.player-info {
  display: flex;
  align-items: center;
  gap: 1rem;
  position: absolute;
  bottom: 2rem;
  left: 1rem;
}

.avatar-container-pos {
  display: flex;
  align-items: center;
}

.avatar-container {
  position: relative;
  height: 6rem;
  width: 6rem;
}

.user-avatar {
  border-color: #ffffff;
  border-radius: 50%;
  border-style: solid;
  border-width: 0.25rem;
  display: block;
  height: 100%;
  left: 0;
  min-height: 100%;
  min-width: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  width: 100%;
  z-index: 1;
}

.view {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.5rem;
}

.view-info {
  display: flex;
  align-items: flex-end;
  gap: 0.5rem;
  margin-left: 2rem;
}

.view-svg {
  height: 1.125rem;
}

.username-container {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.platform-icon {
  height: 1.5rem;
  width: 1.5rem;
  fill: currentColor;
  color: #ffffff;
}

.username {
  font-weight: bold;
  font-size: 1rem;
}

.tabs {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background: rgba(49, 54, 77, 0.9);
  color: white;
  display: flex;
  gap: 1rem;
  padding: 1rem;
  justify-content: flex-start;
  border-bottom-left-radius: 1rem;
  border-bottom-right-radius: 1rem;
  padding-left: 9rem;
}

.tabs-description{
  color: white;
}

.content{
  display: flex;
  flex-direction: row;
}

/* .maps{
} */

.rank-image{
  height: 1.5rem;
}

.table-th{
  /* padding: .5rem; */
}

table.maps {
  border-collapse: collapse;
  border: none;
}

table.maps th,
table.maps td {
  border: none;
}

table.maps tr {
  border-bottom: 1px solid #ccc; 
}

.table_column--left{
  padding: .5rem;
}

.table_column--center{
  padding: .5rem;
}

.table_column--right{
  padding: .5rem;
}

table.maps td{
  font-size: 1.125rem;
  font-weight: 600;
}

.d2{
  background-image: url(../assets/d2bg.jpg);
  background-position: 50%;
}

.vertigo{
  background-image: url(../assets/vertigobg.webp);
  background-position: 50%;
}

.mirage{
  background-image: url(../assets/miragebg.jpg);
  background-position: 50%;
}

.ancient{
  background-image: url(../assets/ancientbg.jpg);
  background-position: 50%;
}

.nuke{
  background-image: url(../assets/nukebg.webp);
  background-position: 50%;
}

.inferno{
  background-image: url(../assets/infernobg.webp);
  background-position: 50%;
}

.overpass{
  background-image: url(../assets/overpassbg.webp);
  background-position: 50%;
}

.train{
  background-image: url(../assets/trainbg.webp);
  background-position: 50%;
}

.anubis{
  background-image: url(../assets/anubisbg.jpg);
  background-position: 50%;
}
</style>
