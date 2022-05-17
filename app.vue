<template>
  <div id="main">
    <div class="container">
      <div class="text title">
        VALE PRODIGY!<br />
        PARTY
      </div>
      <div class="text main">
        <ul>
          <li>Helena provides the house</li>
          <li>Heleni provides the drinks</li>
          <li>Konstantinos is on the music</li>
        </ul>
      </div>
      <div class="text">
        <ul>
          Be ready to:
          <li>drink</li>
          <li>party</li>
          <li>smack your bitch up</li>
        </ul>
      </div>
      <div class="text">when: Saturday, 21st of May</div>
      <div class="text">where: Helena's house, more info on text</div>
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

ul {
  list-style: none;
}

@font-face {
  font-family: "thePartyFont";
  src: url("./assets/party-font.ttf");
}

#main {
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: center;
  align-items: center;
  align-content: center;
  background-image: url("./assets/background.webp");
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color: #464646;
  height: 100vh;
}

.text {
  text-align: center;
  color: white;
  font-size: 200%;
}

.container{
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: center;
  align-items: center;
  align-content: center;
}

.container::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  height: 50%;
  width: 100%;
  background: linear-gradient(180deg, rgba(37,32,30, 0), rgba(37,32,30, 100));
  mix-blend-mode: multiply;
  opacity: 1;
}

.title {
  font-size: 500%;
  color: #79112b;
  font-weight: bolder;
}
</style>
