<template>
  <div id="main">
    <div class="text title ">VALE PRODIGY!<br> PARTY</div>
    <div class="text main">
      <ul>
        <li>Helena provides the house</li>
        <li>Heleni provides the drinks</li>
        <li>Konstantinos is on the music</li>
      </ul>
    </div>
    <div class="text info">Be ready to:
     <ul>
        <li>drink</li>
        <li>party</li>
        <li>dance to Prodigy</li>
        <li>smack your bitch up</li>
      </ul> 
    </div>
  </div>
</template>
<style>
html,
body {
  width: 100%;
  height: 100%;
  margin: 0;
  font-family: thePartyFont;
}

@font-face {
  font-family: "thePartyFont";
  src: url("./assets/party-font.ttf");
}

#main {
  display:block;
  box-sizing: border-box;
  background-image: url("./assets/background.webp");
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color: #464646;
  height: 100vh;
}

.text {
  text-align: right;
  color: white;
  padding-top: 15vw;
}

.text::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  height: 50%;
  width: 100%;
  background: linear-gradient(180deg, rgba(#25201e, 0), #25201e);
  mix-blend-mode: multiply;
  opacity: 0.5;
}

.info {
  font-size: large;
}

.title {
  font-size: xx-large;
  color: #79112b;
  font-weight: bolder;
}
</style>