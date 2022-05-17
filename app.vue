<template>
  <div id="main">
    <div class="text title ">ΒΑΛΕ PRODIGY!<br> PARTY</div>
    <div class="text main">Η Έλενα βάζει το σπίτι (την πιάσαμε κότσο), η Ελένη τα ποτά (μερικά) και ο Κωνσταντίνος
      μουσική (βασικά PRODIGY)
    </div>
    <div class="text info">Πληροφορίες από αυτόν που σου έστειλε το link</div>
  </div>
</template>
<style>
html,
body {
  width: 100%;
  height: 100%;
  margin: 0;
}

#main {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: flex-end;
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
  font-size: x-small;
}

.title {
  font-size: x-large;
  color: #79112b;
  font-weight: bolder;
}
</style>