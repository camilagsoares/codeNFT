<template>
  <div>
    <div class="separationHeader">
      <h1>CodeNFT</h1>
      <ul>
        <li><a href="#home">Inicio</a></li>
        <li><a href="#about">nft</a></li>
        <li><a href="#contact">colaboradores </a></li>
        <li><a href="#contact">perguntas </a></li>
      </ul>
    </div>
    <span class="textDescubra"
      >Descubra e colete
      <p class="textGradient">obras de arte</p>
      digitais super raras</span
    >
    <p>
      O maior mercado NFT. Criação digital autêntica e verdadeiramente única.
      Assinado e emitido pelo criador, possibilitado pela tecnologia blockchain
    </p>
    <button class="btn">EXPLORAR</button>

    <h2>TOP NFT'S</h2>

    <img alt="Vue logo" src="../assets/image1.png" class="img" />
    <img alt="Vue logo" src="../assets/image2.png" />
    <img alt="Vue logo" src="../assets/image3.png" />

    <OsColecionadores />
  </div>
</template>

<script>
import OsColecionadores from "./OsColecionadores.vue";

export default {
  name: "HeaderMenu",
  props: {
    msg: String,
  },
  components: {
    OsColecionadores,
  },
};
</script>

<style scoped>
.separationHeader {
  display: flex;
  justify-content: space-between;
}
h1,
h2 {
  font-family: "Jura", sans-serif;
  color: white;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.textDescubra {
  font-family: "Inter", sans-serif;
  font-weight: 700;
  font-size: 40px;
}

.textGradient {
  font-size: 48px;
  background-image: linear-gradient(to right, #ff8d8d 0%, #f7fc0e 100%);
  -webkit-background-clip: text;
  -moz-background-clip: text;
  background-clip: text;
  color: transparent;
}

.btn {
  width: 245px;
  height: 56px;
  left: 352px;
  top: 624px;

  background: linear-gradient(97.86deg, #ff8d8d -38.38%, #f7fc0e 71.88%);
  border-radius: 6px;
}

img {
  margin: 10px 20px 30px 40px;
}
</style>
